---
title: Binary Calculator
layout: default
description: HTML and JavaScript.
author: Amay Advani
---


<html>
    <head>
        <meta charset="utf-8"/>
        <!-- this tag makes is so that the browser can translate the code-->
        <title>Binary Calculator</title>
        <!--this bootstrap allows me to import javascript and html design and templates-->
    </head>
    <body>
    <!--this div tag allows me to group coded content together or a division tag -->
         <div class="container">
    <!--jumbotron is a class modified by the bootstrap that allows me to customize -->
            <div class="jumbotron">
                <h1>Binary Calculator</h1>
                <div id="output"></div>
                <div class="container mt-2">
                    <div class="row">
                        <div class="col-12">
                            <button type="button" 
                                    class="btn btn-light" 
                                    onclick="input('0')">
                                      0</button>
                            <button type="button" 
                                    class="btn btn-light" 
                                    onclick="input('1')">
                                      1</button>
                            <button type="button" 
                                    class="btn btn-warning float" 
                                    onclick="backspace()">
                                      backspace</button>
                        </div>
                    </div>
                    <div class="row mt-2">
                        <div class="col-12">
                            <button type="button" 
                                    class="btn btn-info" 
                                    onclick="input('+')">+</button>
                            <button type="button"
                                    class="btn btn-info" 
                                    onclick="input('-')">-</button>
                            <button type="button" 
                                    class="btn btn-info" 
                                    onclick="input('*')">*</button>
                            <button type="button" 
                                    class="btn btn-info" 
                                    onclick="input('/')">/</button>
                        </div>
                    </div>
                    <div class="row mt-2">
                        <div class="col-12">
                            <button type="button" 
                                    class="btn btn-success" 
                                    onclick="calculate()">calculate!!!</button>
                                    </div>
                    </div>
                </div>
            </div>
        </div>
        <!--jquery and popper.js cdn -->
        <script src=
"https://code.jquery.com/jquery-3.5.1.slim.min.js" 
                integrity=
"sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" 
                crossorigin="anonymous"></script>
        <script src=
"https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" 
                integrity=
"sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" 
                crossorigin="anonymous"></script>
    </body>
</html>

<!--for this css i had to ask my classmates how to change the backgroup using the !important function-->

<style>
    
    h1{
        background-color: grey;
        min-width: 120px;
        border: 2px solid black;
    }

    .jumbotron{
      width : 70%;
      margin-top: auto;
      margin-bottom: auto;
      margin-left: auto;
      margin-right: auto;
      text-align: center;
      height: 400px; 
      background-color: lightblue !important;
    }
  
    #output{
      border: 2px solid black;
      min-height: 60px;
      text-align: right;
      font-weight: bold;
      font-size: 20px;
      background-color: darkgrey !important;
    }
  
    .btn{
      min-width: 120px;
      border: 2px solid black;
      background-color: lightgray !important;
    }
    container mt-2{
        margin-top: auto;
        margin-bottom: auto;
        margin-left: auto;
        margin-right: auto;
    }

</style>

 