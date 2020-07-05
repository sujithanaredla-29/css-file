<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-image:url("https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS7_vwhkBu1Xj77nap-2wKaDg1Y1wvWwe7UlY_Z-BEaxAvYqDeM&usqp=CAU");
        }
        .flex-container{
            display:flex;
            margin:10px;
            padding:30px;
            font-size:30px ;
            justify-content: space-between;
            overflow-y: scroll y;
            
        }
        h1{
            text-align: center;
        }
        #one{
            border: 1px solid black;
            background-color:blanchedalmond;
        }
        #two{
            border: 1px solid black;
            background-color:blanchedalmond;
        }
        #two1{
            border:1px solid black;
            background-color: blanchedalmond;

        }
        #two2{
            border:1px solid black;
            background-color: blanchedalmond;
        }
        #three{
            border: 1px solid black;
            background-color:blanchedalmond;
        }
        #four{
            border: 1px solid black;
            background-color:blanchedalmond;
        }
        #five{
            border:1px solid black;
            background-color: blanchedalmond;

        }
        button{
            color: olive;
        }
    </style>
</head>
<body>
    <form>
        <i class="fas-fa-home"></i>
        <h1>Tralala</h1>
        <div class="flex-container">
            <div id="one">
                <ol>
                    <p>Todo                      ...</p>
                    <label for="name"></label>
                    <input type="text" id="name" name="name" />
                    <br />
                    <label for="name"></label>
                    <input type="text" id="name" name="name" />
                    <br />
                    
                    <p>+add another card</p>
                </ol>
            </div>
            <div id="two">
                <ol>
                    <p>Doing                 ...</p>
                    <label for="name"></label>
                    <input type="text" id="name" name="name" />
                    <br />
                     <p>+add another card</p>
                </ol>
            </div>

           <div id="two1">
               <ol>
                   <p>Testing/Verifying           ...</p>
                   <label for="name"></label>
                   <input type="text" id="name" name="name" />
                   <br />
                   <p>+add another card</p>
               </ol>
           </div>
           <div id="two2">
               <ol>
                   <p>Deploying                    ...</p>
                   <label for="name"></label>
                   <input type="text" id="name" name="name" />
                   <br />
                   <p>+add another card</p>
               </ol>
           </div>
            <div id="three">
                <ol>
                    <p>Done                    ...</p>
                    <p>+add card</p>
                </ol>

            </div>

            <div id="four">
                <p>+add another list</p>
            </div>
            <div id="five">
                <ol>
                <label for="name">enter title</label>
                <textarea id="name" rows="4"></textarea>
                <button>enter list</button>
                </ol>
            </div>
        </div>
    </form>
</body>
</html>
