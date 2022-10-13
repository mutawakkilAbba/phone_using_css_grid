<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Phone</title>
    <style>
      * {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
        font-family: sans-serif;
      }
      .container::after {
        content: "New Phone";
        position: absolute;
        background-color: rgba(0, 255, 242, 0.541);

        top: -5px;
        left: -85px;
        border-radius: 5px;
        padding: 3px;
        font-weight: bold;
      }
      .container {
        position: relative;
        border: 5px solid rgba(0, 0, 0, 0.548);
        width: 240px;
        height: 500px;
        border-radius: 20px;
        margin: 0 auto;
        box-shadow: 0px 20px 20px;
        margin-top: 30px;
      }
      .phone-head {
        background-color: black;
        border-radius: 15px 15px 0px 0px;
        height: 30px;
        display: flex;
        justify-content: center;
        align-items: center;
      }
      .cemera {
        background-color: aliceblue;
        height: 10px;
        width: 10px;
        border-radius: 10px;
      }
      .speaker {
        background-color: aliceblue;
        height: 10px;
        width: 50px;
        border-radius: 5px;
        margin-left: 10px;
      }
      .screen {
        /* border: 5px solid black; */
        width: 230px;
        height: 280px;
        /* border-radius: 10px; */
        background-color: aqua;
      }
      .head-container {
        display: flex;
        justify-content: center;
        gap: 2px;
        margin-bottom: 2px;
      }
      .middle-button {
        border: 2px double black;
        padding: 10px;
        border-radius: 10px;
        width: 85px;
        height: 50px;
      }
      .left-button-con {
        /* border: 2px solid; */
        width: 90px;
        text-align: center;
      }
      .rigth-button-con {
        /* border: 2px solid; */
        width: 90px;
        text-align: center;
      }
      .left-button-one {
        border: 2px solid;
        font-weight: bold;
        border-radius: 5px 5px 0px 0px;
      }
      .left-button-two {
        border: 2px solid;
        font-weight: bold;
        border-radius: 0 0px 5px 5px;
      }
      .rigth-button-one {
        border: 2px solid;
        font-weight: bold;
        border-radius: 5px 5px 0px 0px;
      }
      .rigth-button-two {
        border: 2px solid;
        font-weight: bold;
        border-radius: 0px 0px 5px 5px;
      }
      .key-container {
        display: grid;
        /* grid-template-columns: repeat(1fr 10px); */
        grid-template-columns: 1fr 1fr 1fr;
        justify-content: center;
        align-items: center;
        gap: 2px;
        row-gap: 5px;
      }
      .key {
        border: 2px solid;
        text-align: center;
        font-weight: bold;
        border-radius: 3px;
      }
      .footer {
        background-color: black;
        height: 28px;
        border-radius: 0px 0px 15px 15px;
        color: aliceblue;
        text-align: center;
        font-size: 16px;
        margin-top: 2px;
      }
      .rigth-button-con {
        display: flex;
        flex-direction: column;
        /* column-gap: 2px; */
        gap: 2px;
      }
      .left-button-con {
        display: flex;
        flex-direction: column;
        /* column-gap: 2px; */
        gap: 2px;
      }
      .under-screen {
        background-color: black;
        width: 100%;
      }
      .fotter-text {
        font-size: 15px;
        /* margin-top: ; */
        color: rgb(133, 133, 133);
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="phone-head">
        <div class="cemera"></div>
        <div class="speaker"></div>
      </div>

      <div class="screen"></div>
      <div class="under-screen"></div>
      <div class="head-container">
        <div class="left-button-con">
          <div class="left-button-one">--</div>
          <div class="left-button-two">--</div>
        </div>
        <div class="middle-button"></div>
        <div class="rigth-button-con">
          <div class="rigth-button-one">--</div>
          <div class="rigth-button-two">--</div>
        </div>
      </div>

      <div class="key-container">
        <div class="key key-1">1</div>
        <div class="key key-2">2</div>
        <div class="key key-3">3</div>

        <div class="key key-4">4</div>
        <div class="key key-5">5</div>
        <div class="key key-6">6</div>

        <div class="key key-7">7</div>
        <div class="key key-8">8</div>
        <div class="key key-9">9</div>

        <div class="key key-10">#</div>
        <div class="key key-11">0</div>
        <div class="key key-12">*</div>
      </div>

      <div class="footer"><p class="fotter-text">TexNo</p></div>
    </div>
  </body>
</html>
