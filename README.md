# task2.css

header {
  background-color: navy blue;
  display: flex;
  justify-content: space-between;
  padding: 25px;
}
nav ul {
  display: flex;
  list-style: none;
}
nav a {
  color: black;
  text-decoration: none;
  padding: 15px 25px;
}

  /* Style the cover photo */
.cover-photo img {
    width: 100%;
}

video{
  width: 100%;
  height: 300px;
  object-fit: fill;

}

/* profile */
#profile {
  display: flex;
  align-items: center;
  padding: 50px;
  background-color: rebeccapurple;
}

#picture-container {
  width: 0%;
  text-align: center;
}

#picture-container img {
  width: 250px;
  height: 250px;
  border-radius: 50%;
  margin-bottom: 20px;
  margin-left: 100px;
}

#bio-container {
  width: 60%;
  text-align: left;
  padding-left: 50px;
}

#bio-container h1 {
  color: white;
}
