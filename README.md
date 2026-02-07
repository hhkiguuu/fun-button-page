<title>Question</title> <style> body { font-family: Arial, sans-serif; text-align: center; margin: 30px 10px; }
h1 {  
  font-size: 28px;  
}  

.buttons {  
  margin-top: 30px;  
  position: relative;  
  height: 150px;  
}  

button {  
  font-size: 18px;  
  padding: 12px 25px;  
  cursor: pointer;  
  position: absolute;  
  transition: all 0.3s ease;  
}  

#yesBtn {  
  left: 30%;  
}  

#noBtn {  
  left: 55%;  
}  

#result {  
  margin-top: 30px;  
}  

#emoji {  
  max-width: 80%;  
  height: auto;  
  display: none;  
}  

/* Make buttons stack on small screens */  
@media (max-width: 500px) {  
  #yesBtn, #noBtn {  
    position: static;  
    display: inline-block;  
    margin: 10px;  
    width: 40%;  
  }  
  .buttons {  
    height: auto;  
  }  
}  
</style>
Can I see your tits?

Yes No
emoji
<script> const yesBtn = document.getElementById("yesBtn"); const noBtn = document.getElementById("noBtn"); const emoji = document.getElementById("emoji"); yesBtn.onclick = () => { emoji.style.display = "block"; }; noBtn.onmouseover = () => { // Only move on screens wider than 500px if (window.innerWidth > 500) { const x = Math.random() * 70; const y = Math.random() * 60; noBtn.style.left = x + "%"; noBtn.style.top = y + "px"; } }; </script>
