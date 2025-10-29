body {
  margin: 0;
  font-family: "Segoe UI", Arial, sans-serif;
  background-image: url(FINAL/Imagen/Imageninicio.png);
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  color: #1e1f15;
}


header {
  background: linear-gradient(135deg, #0b240b, #71bb83, #1e1f15);
  padding: 1%;
  color: #eefaee;
  text-align: left;
  display: flex;
  align-items: center;
  gap: 20px;
}

header img {
  width: 75px;
  height: 70px;
  margin-left: 10px;
}

.inicio {
  text-align: center;
  padding: 60px 20px;
}

.inicio h2 {
  color: #0b240b;
  font-size: 32px;
  margin-bottom: 25px;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.contenido {
  background-color: rgba(255, 255, 255, 0.9);
  border-left: 6px solid #008834;
  margin: 0 auto;
  padding: 25px;
  max-width: 800px;
  border-radius: 10px;
  box-shadow: 2px 4px 15px rgba(0, 0, 0, 0.2);
  text-align: left;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.contenido:hover {
  transform: translateY(-5px);
  box-shadow: 4px 8px 20px rgba(0, 0, 0, 0.3);
}

.contenido p {
  font-size: 16px;
  line-height: 1.6;
  color: #1e1f15;
}
.slogan {
  background-color: #afffc3;
  
  margin: 40px auto;
  padding: 20px;
  max-width: 800px;
  text-align: left;
}
.slogan h1{
  text-align: center;
  color: #000000;
}
.slogan p{
  text-align:center;
  font-size: 14px;
   color: #000000;
}

.servicios {
  text-align: center;
  padding: 40px 20px;
}

.servicios h2 {
  color: #000000;
  margin-bottom: 30px;
    font-size: 40px;
}

.ordenar {
  display: flex;
  justify-content: space-between;  
  align-items: stretch;
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
  gap: 20px;
}

.servicio-DAW{
  background-color: #ffffff;
  border-left: 5px solid #3498db;
  border-radius: 10px;
  box-shadow: 2px 4px 10px rgba(0, 0, 0, 0.1);
  padding: 30px;
  width: 350px;
  text-align: left;
  transition: transform 0.3s
}
.servicio-DAM{
  background-color: #ffffff;
  border-left: 5px solid #3498db;
  border-radius: 10px;
  box-shadow: 2px 4px 10px rgba(0, 0, 0, 0.1);
  padding: 30px;
  width: 350px;
  text-align: left;
  transition: transform 0.3s, 
}
.servicio-ASIX {
  background-color: #ffffff;
  border-left: 5px solid #3498db;
  border-radius: 10px;
  box-shadow: 2px 4px 10px rgba(0, 0, 0, 0.1);
  padding: 30px;
  width: 350px;
  text-align: left;
  transition: transform 0.1s
}

.servicio-DAW:hover{
  box-shadow: 6px 8px 15px rgba(0, 0, 0, 0.2);
}
.servicio-DAM:hover{
  box-shadow: 15px 8px 15px rgba(0, 0, 0, 0.2);
}
.servicio-ASIX:hover {
  box-shadow: 15px 8px 15px rgba(0, 0, 0, 0.2);
}

.servicio-emoji {
  font-size: 50px;
  text-align: center;
  margin-bottom: 15px;
}

.servicio-contenido h3 {
  color: #008834;
  margin-bottom: 10px;
}

.servicio-contenido p {
  font-size: 14px;
  line-height: 1.5;
  text-align: justify;
}

footer {
  background: linear-gradient(135deg, #0b240b, #71bb83, #1e1f15);
  color: #ffffff;
  text-align: center;
  padding: 20px;
  margin-top: 50px;
}

footer p {
  margin: 5px 0;
  font-size: 14px;
}

