Ejemplo de logueo con facebook y twitter en nodejs con passportjs 

npm install

y correr con 

npm start

importante 

crear archivo config.js donde se crea un objeto y exportarlo. por ejemplo




var config = {
  twitter: {
    key: 'KEY TWITTER',
    secret: 'SECRET KEY'
  },
  facebook: {
    id: 'CLIENT ID',
    secret: 'SECRET KEY'
  }
};

module.exports = config;

Y LISTO!