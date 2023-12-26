* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family:gilroy;
    color: black;
}
html,
body {
    height: 100%;
    width: 100%;
}

#main{
    min-height: 100%;
    width: 100%;
    background-color:bisque;
    padding: 100px 0;
    display:flex;
    align-items: center;
    justify-content: center;
    background-image: url(b2.jpg);
    flex-direction: column;
}
#main>h1{
    font-size: 48px;
    display: flex;
    align-items: center;
    background-color: bisque;
}
#main>h1 span{
    margin: 0 15px;
    display: flex;
    align-items: center;
}
#main>h1 span img{
    height: 40px;
    rotate: 0deg;
    transition: 0.3s ease;
}
#main #endec-div{
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: wheat;
    border-radius: 10px;
    padding: 8px ;
    width: 28%;
    margin: 35px 0;
}
#endec-div h3{
    font-size: 17px;
    display: flex;
    border-radius: 8px;
    font-weight: 500;
    align-items: center;
    /* background-color: red; */
    cursor: pointer;
    padding: 12px 10px;
    transition: 0.2s ease;
}
#enc-btn{
    background-color: antiquewhite;
}
#endec-div h3 span{
    display: flex;
    align-items: center;
    margin-right: 10px;
}
#endec-div h3 img{
    height: 20px;
}
#encryption{
    width: 45%;
    display: flex;
    align-items: flex-start;
    flex-direction: column;
    justify-content: space-around;
}

#encryption h5{
    font-size: 16px;
    font-weight: 500;
    color: black;
    margin-bottom: 13px;
}
#encryption textarea{
    width: 100%;
    height: 70px;
    border: 1px solid black;
    padding: 10px;
    margin-bottom: 50px;
    border-radius: 8px;
    font-size: 17px;
    outline: none;
   
}
#encryption input{
    width: 100%;
    border: 1px solid black;
    padding: 10px;
    margin-bottom: 50px;
    border-radius: 8px;
    font-size: 16px;
    outline: none;
    
}

#encryption button{
    display: flex;
    align-items: center;
    color: blue;
    background-color: bisque;

    border: none;
    width: 100%;
    justify-content: center;
    padding: 10px;
    border-radius: 10px;
    
    font-size: 17px;
}
button span{
    display: flex;
    margin-right: 10px;
    border-color: blue;
}
button img{
    height: 20px;
}

#decryption{
    width: 45%;
    display: flex;
    align-items: flex-start;
    flex-direction: column;
    justify-content: space-around;
    display: none;
    background-color: bisque;
}

#decryption h5{
    font-size: 16px;
    font-weight: 500;
    color:black;
    margin-bottom: 13px;
}
#decryption textarea{
    width: 100%;
    height: 70px;
    border: 1px solid black;
    padding: 10px;
    margin-bottom: 50px;
    border-radius: 8px;
    font-size: 17px;
    outline: none;
    
}
#decryption input{
    width: 100%;
    border: 1px solid black;
    padding: 10px;
    margin-bottom: 50px;
    border-radius: 8px;
    font-size: 16px;
    outline: none;
   
}

#decryption button{
    display: flex;
    align-items: center;
    color: blue;
    background-color: white;

    border: solid black;
    width: 100%;
    justify-content: center;
    padding: 10px;
    border-radius: 10px;
   
    font-size: 17px;
}
button span{
    display: flex;
    margin-right: 10px;
    border-color: blue;
}
button img{
    height: 40px;
}

#result{
    padding: 20px;
    border-radius: 10px;
    font-size: 18px;
   
    background-color: beige;
    border: 1px solid black;
    width: 45%;
    display: "none";
    margin-top: 40px;
}
