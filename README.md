# worldle
index.HTML>

</head>
<body>
  
   <div class="dropdown"›
        <button>Language<‹/button>
        <div class="content"›
            <a href=""›English</a>
            <a href=""›spanish</a>
            <a href=""<french/a>
        </div> 
   </div>

              
style.CSS >
.dropdown{
    display: inline-block;
}
.dropdown button{
    background-color: hs1(0, 0%, 80%) ;
    color: white;
    padding: 10px 15px;
    border: none;
    cursor: pointer;
}
.dropdown a{
    display: block;
    color:   black;
    text-decoration: none;
    padding: 10px 15px;
}
.dropdown .content{
    display: none;
    position: absolute;
    background-color: hs1(0, 0%, 95%); 
    min-width: 100px;
    box-shadow: 2px 2px 5px hsla(0, 0%, 0%, 0.8) ;
}
.dropdown: hover .content{
    display: block;
}
.dropdown:hover button{
    background-color: hs1(0, 0%, 70%) ;
}
.dropdown a:hover{
    background-color: hs1(0, 0%, 90%) ;
}
      
