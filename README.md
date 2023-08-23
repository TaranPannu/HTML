* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.top-container{
    width: 100%;

 padding: 30px;
    list-style: none;
    text-align: center;
    background-color: rgb(38, 2, 96);
    color: white;
}
#name{
    margin-top: 30px;
    font-size: 3.5rem;
   font-weight: 800px;
   margin-right: 100px;
}
li{
    display: inline; 
   padding: 20px;
   font-size: 1.2rem;
}
.hover:hover {
    color: rgb(5, 96, 186);
    cursor: pointer;
}
.container-1{
    height:500px;
    background-color: rgb(38, 2, 96);
    
}
.container-1-1{
    background-color: rgb(38, 2, 96);
display: flex;
}
.profile-pic {
    width: 300px;
    height: 300px;
    border-radius: 50%; /* To make it circular */
    position: absolute;
    left: 900px;
    top: 190px;
    transition: transform 1.5s, border 1.5s;
}

.profile-pic:hover {
    transform: scale(1.2); /* Zoom in on hover */
    border: 5px solid rgb(244, 243, 246); /* Add a border on hover */
}

.cont-img {
    background-color: rgb(38, 2, 96);
    width: 100%;
    height: 130px; /* Adjust height as needed */
    position: absolute;
  
}
.title{
    color: white;
    position: relative;
    top: 100px;
    left: 220px;
    font-size: 2.0rem;
    font-weight: 800px;
}

.soft{
    color: white;
display: flex;
flex-flow: row;
flex-direction: row;
font-size:35px;
position: relative;

top: 120px;
    left: 220px;
}
.space{
    width: 10px;
}
.software  {

        animation: so-ft 3.2s ease infinite alternate both, opacity 6.2s ease 1110s infinite both; 
}
s{
animation-delay:0.0s; ;
}
.o{
    animation-delay:0.2s ;
    }
    .f{
        animation-delay:0.4s ;
        }
        .t{
            animation-delay:0.6s ;
            }
 
            .w{
                animation-delay:0.8s; ;
                }
                .a{
                    animation-delay:1s ;
                    }
                    .r{
                        animation-delay:1.2s ;
                        }
                        .e{
                            animation-delay:1.4s ;
                            }
                            .dd{
                                animation-delay:1.6s; 
                                }
                                .E{
                                    animation-delay:1.8s ;
                                    }
                                    
                                    .vv{
                                        animation-delay:2s ;
                                        }.E2{
                                            animation-delay: 2.2s;
                                        }
                                        .ll{
                                            animation-delay:2.4s ;
                                            }
                                 
                                            .oo{
                                                animation-delay:2.6s; 
                                                }
                                                .pp{
                                                    animation-delay:2.8s ;
                                                    }
                                                    .ee{
                                                        animation-delay:3s ;
                                                        }
                                                        .rr{
                                                            animation-delay:3.2s ;
                                                            }
                                

@keyframes so-ft {
    from {
        transform: translateY(-15px);
    }
    to {
        transform: translateY(15px);
    }
}
@keyframes opacity {
    0% {
        opacity: 1;
    }


    100% {
        opacity: 0;
    }
}









