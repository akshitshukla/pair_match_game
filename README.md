# pair_match_game
<!DOCTYPE html>
<html>
<head>
    <!-- Information about the page -->
    <!--This is the comment tag-->
     
    
</head>
 
<body>
    <!--Contents of the webpage-->
 <p><h1> <a href="https://html-css-js.com/?html=%3C!DOCTYPE%20html%3E%0A%3Chtml%20lang=%22en%22%3E%0A%3Chead%3E%0A%20%20%20%20%3Cmeta%20charset=%22UTF-8%22%3E%0A%20%20%20%20%3Cmeta%20http-equiv=%22X-UA-Compatible%22%20content=%22IE=edge%22%3E%0A%20%20%20%20%3Cmeta%20name=%22viewport%22%20content=%22wi$*$dth=device-wi$*$dth,%20initial-scale=1.0%22%3E%0A%20%20%20%20%3Ctitle%3EPair%20Match%20Game%3C/title%3E%0A%20%20%20%20%3Clink%20rel=%22shortcut%20icon%22%20type=%22image/jpg%22%20href=%22Images/fevicon.PNG%22/%3E%0A%20%20%20%20%3Clink%20rel=%22stylesheet%22%20href=%22gameStyle.css%22%3E%0A%20%20%20%20%3Cscript%20src=%22https://code.jquery.com/jquery-3.2.1.min.js%22%3E%20%3C/script%3E%0A%20%20%20%20%3Cscript%20src=%22gameScript.js%22%3E%20%3C/script%3E%0A%3C/head%3E%0A%3Cbody%3E%0A%20%20%20%20%3Cdiv%20i$*$d=%22ol%22%3E%20%3C/div%3E%0A%20%20%20%20%3Cdiv%20style=%22height:%208px;%22%3E%3C/div%3E%0A%20%20%20%20%3Cdiv%20i$*$d=%22title%22%3E%0A%20%20%20%20%3Cspan%20i$*$d=%22logo%22%3EPAIR%20MATCH%20GAME%3C/span%3E%0A%20%20%20%20%3C/div%3E%0A%0A%20%20%20%20%3Cdiv%20i$*$d=%22title%22%20style=%22height:%2040px;%22%3E%0A%20%20%20%20%20%20%20%20%3Cspan%20i$*$d=%22moves%22%3E%3C/span%3E%0A%20%20%20%20%20%20%20%20%3Cspan%20i$*$d=%22time%22%3E%3C/span%3E%0A%20%20%20%20%3C/div%3E%0A%0A%20%20%20%20%3Ccenter%3E%0A%20%20%20%20%20%20%20%20%3Ctable%20cellspacing=%220%22%3E%3C/table%3E%0A%20%20%20%20%3C/center%3E%0A%3C/body%3E%0A%3C/html%3E&css=@import%20url('https://fonts.googleapis.com/css2?family=Biryani:wght@800$**$display=swap');%0A*%20%7B%0A%20%20%20%20font-family:%20'Biryani',%20sans-serif;%0A%7D%0Ahtml%20%7B%0A%20%20%20%20wi$*$dth:100vw;%0A%20%20%20%20height:100%25;%0A%7D%0Abody%20%7B%0A%20%20%20%20margin:0px;%0A%20%20%20%20background-image:%20-webkit-gradient(linear,%20left%20top,%20left%20bottom,%20from(#4481eb),%20to(#04bedd));%0A%20%20%20%20background-image:%20-o-linear-gradient(top,%20#4481eb%200%25,%20#04bedd%20100%25);%0A%20%20%20%20background-image:%20linear-gradient(to%20bottom,%20#4481eb%200%25,%20#04bedd%20100%25);%0A%7D%0A%0Ap%20%7B%0A%20%20%20%20font-size:%2040px;%0A%20%20%20%20margin-top:5px;%0A%7D%0Atd%20%7B%0A%20%20%20%20background-color:%20transparent;%0A%20%20%20%20height:70px;%0A%20%20%20%20wi$*$dth:70px;%0A%7D%0Atd,%20.inner,%20.front,%20.back%20%7B%0A%20%20%20%20border-radius:%204px;%0A%7D%0Atable%20%7B%0A%20%20%20%20margin-top:%2080px;%0A%7D%0A%0A#inst%20%7B%0A%20%20%20%20wi$*$dth:%2085vw;%0A%20%20%20%20background-color:%20rgba(255,255,255,0.1);%0A%20%20%20%20text-align:%20center;%0A%20%20%20%20margin-top:16vh;%0A%20%20%20%20-webkit-backdrop-filter:%20blur(10px);%0A%20%20%20%20%20%20%20%20%20%20%20%20backdrop-filter:%20blur(10px);%0A%20%20%20%20border:%200.2px%20soli$*$d%20#ffff;%0A%20%20%20%20border-radius:%2010px;%0A%20%20%20%20padding:%205px;%0A%7D%0A#inst%20li%20%7B%0A%20%20%20%20text-align:%20left;%0A%20%20%20%20padding:%205px;%0A%7D%0A%0Abutton%20%7B%0A%20%20%20%20background-color:%20rgba(255,255,255,0.2);%0A%20%20%20%20-webkit-backdrop-filter:%20(20px);%0A%20%20%20%20backdrop-filter:%20(20px);%0A%20%20%20%20color:%20white;%0A%20%20%20%20margin:%205px;%0A%20%20%20%20border:%200.1px%20soli$*$d%20#ffff;%0A%20%20%20%20border-radius:%2010px;%0A%20%20%20%20font-weight:%20smaller;%0A%20%20%20%20wi$*$dth:100px;%0A%20%20%20%20font-size:18px;%0A%20%20%20%20padding:5px;%0A%7D%0A%0A#ol%20%7B%0A%20%20%20%20position:%20absolute;%0A%20%20%20%20height:100vh;%0A%20%20%20%20wi$*$dth:100vw;%0A%20%20%20%20background-color:%20rgba(0,0,200,0.1);%0A%20%20%20%20color:%20white;%0A%20%20%20%20-webkit-backdrop-filter:%20blur(8px);%0A%20%20%20%20%20%20%20%20%20%20%20%20backdrop-filter:%20blur(8px);%0A%20%20%20%20z-index:2;%0A%20%20%20%20%0A%7D%0A#iol%20%7B%0A%20%20%20%20text-align:%20center;%0A%20%20%20%20position:%20absolute;%0A%20%20%20%20wi$*$dth:%20100vw;%0A%20%20%20%20top:%2035vw;%0A%7D%0A%0A#title%20%7B%0A%20%20%20%20background-color:%20rgba(255,255,255,0.25);%0A%20%20%20%20-webkit-backdrop-filter:%20blur(15px);%0A%20%20%20%20%20%20%20%20%20%20%20%20backdrop-filter:%20blur(15px);%0A%20%20%20%20border-radius:10px;%0A%20%20%20%20margin:%208px;%0A%20%20%20%20margin-top:0px;%0A%20%20%20%20color:%20white;%0A%20%20%20%20height:56px;%0A%20%20%20%20text-align:%20center;%0A%7D%0A%0A#time%20%7B%0A%20%20%20%20position:%20absolute;%0A%20%20%20%20right:%2020px;%0A%20%20%20%20font-size:%2016px;%0A%20%20%20%20top:%208.5px;%0A%7D%0A%0A#moves%20%7B%0A%20%20%20%20position:%20absolute;%0A%20%20%20%20left:%2020px;%0A%20%20%20%20font-size:%2016px;%0A%20%20%20%20top:8.5px;%0A%7D%0A%0A#logo%20%7B%0A%20%20%20%20font-size:%2022px;%0A%20%20%20%20padding-top:%2010px;%0A%20%20%20%20display:%20block;%0A%7D%0A%0A.inner%20%7B%0A%20%20%20%20position:%20relative;%0A%20%20%20%20wi$*$dth:%20100%25;%0A%20%20%20%20height:%20100%25;%0A%20%20%20%20text-align:%20center;%0A%20%20%20%20-webkit-transition:%20-webkit-transform%200.8s;%0A%20%20%20%20%20%20%20%20%20%20%20%20transition:%20-webkit-transform%200.8s;%0A%20%20%20%20%20%20%20%20%20-o-transition:%20transform%200.8s;%0A%20%20%20%20%20%20%20%20%20%20%20%20transition:%20transform%200.8s;%0A%20%20%20%20%20%20%20%20%20%20%20%20transition:%20transform%200.8s,%20-webkit-transform%200.8s;%0A%20%20%20%20-webkit-transform-style:%20preserve-3d;%0A%20%20%20%20%20%20%20%20%20%20%20%20transform-style:%20preserve-3d;%0A%20%20%20%20-webkit-transform:%20rotateY(0deg);%0A%20%20%20%20%20%20%20%20%20%20%20%20transform:%20rotateY(0deg);%0A%7D%0A%0A.front%20%7B%0A%20%20%20%20background-color:%20rgba(255,255,255,0.3);%0A%7D%0A%0A.back%20%7B%0A%20%20%20%20background-color:%20rgba(255,255,255,0.5);%0A%20%20%20%20-webkit-transform:%20rotateY(180deg);%0A%20%20%20%20%20%20%20%20%20%20%20%20transform:%20rotateY(180deg);%0A%7D%0A%0A.front,%20.back%20%7B%0A%20%20%20%20position:%20absolute;%0A%20%20%20%20wi$*$dth:%20100%25;%0A%20%20%20%20height:%20100%25;%0A%20%20%20%20-webkit-backface-visibility:%20hi$*$dden;%0A%20%20%20%20%20%20%20%20%20%20%20%20backface-visibility:%20hi$*$dden;%0A%7D%0Abutton:hover,%20button:active%20%7B%0A%20%20%20%20outline:0;%0A%7D%0A%09%20%20&js=var%20em%20=%20%5B%22%F0%9F%92%90%22,%22%F0%9F%8C%B9%22,%22%F0%9F%8C%BB%22,%22%F0%9F%8F%B5%EF%B8%8F%22,%22%F0%9F%8C%BA%22,%22%F0%9F%8C%B4%22,%22%F0%9F%8C%88%22,%22%F0%9F%8D%93%22,%22%F0%9F%8D%92%22,%22%F0%9F%8D%8E%22,%22%F0%9F%8D%89%22,%22%F0%9F%8D%8A%22,%22%F0%9F%A5%AD%22,%22%F0%9F%8D%8D%22,%22%F0%9F%8D%8B%22,%22%F0%9F%8D%8F%22,%22%F0%9F%8D%90%22,%22%F0%9F%A5%9D%22,%22%F0%9F%8D%87%22,%22%F0%9F%A5%A5%22,%22%F0%9F%8D%85%22,%22%F0%9F%8C%B6%EF%B8%8F%22,%22%F0%9F%8D%84%22,%22%F0%9F%A7%85%22,%22%F0%9F%A5%A6%22,%22%F0%9F%A5%91%22,%22%F0%9F%8D%94%22,%22%F0%9F%8D%95%22,%22%F0%9F%A7%81%22,%22%F0%9F%8E%82%22,%22%F0%9F%8D%AC%22,%22%F0%9F%8D%A9%22,%22%F0%9F%8D%AB%22,%22%F0%9F%8E%88%22%5D;%0A%0Avar%20tmp,%20c,%20p%20=%20em.length;%0Aif(p)%20while(--p)%20%7B%0A%20%20%20c%20=%20Math.floor(Math.random()%20*%20(p%20+%201));%0A%20%20%20tmp%20=%20em%5Bc%5D;%0A%20%20%20em%5Bc%5D%20=%20em%5Bp%5D;%0A%20%20%20em%5Bp%5D%20=%20tmp;%0A%7D%0A%0A%0Avar%20pre=%22%22,%20pID,%20ppID=0,%20turn=0,%20t=%22transform%22,%20flip=%22rotateY(180deg)%22,%20flipBack=%22rotateY(0deg)%22,%20time,%20mode;%0A%0A%0Awindow.onresize%20=%20init;%0Afunction%20init()%20%7B%0A%20%20%20W%20=%20innerWi$*$dth;%0A%20%20%20H%20=%20innerHeight;%0A%20%20%20$('body').height(H+%22px%22);%0A%20%20%20$('#ol').height(H+%22px%22);%0A%7D%0A%0A%0Awindow.onload%20=%20function()%20%7B%0A%20%20%20%20$(%22#ol%22).html(%60%3Ccenter%3E%3Cdiv%20i$*$d=%22inst%22%3E%3Ch3%3EWelcome%20!%3C/h3%3EInstructions%20For%20Game%3Cbr/%3E%3Cbr/%3E%3Cli%3EMake%20pairs%20of%20similiar%20blocks%20by%20flipping%20them.%3C/li%3E%3Cli%3ETo%20flip%20a%20block%20you%20can%20click%20on%20it.%3C/li%3E%3Cli%3EIf%20two%20blocks%20you%20clicked%20are%20not%20similar,%20they%20will%20be%20flipped%20back.%3C/li%3E%3Cp%20style=%22font-size:18px;%22%3EClick%20one%20of%20the%20following%20mode%20to%20start%20the%20game.%3C/p%3E%3C/div%3E%3Cbutton%20onclick=%22start(3,%204)%22%3E3%20x%204%3C/button%3E%20%3Cbutton%20onclick=%22start(4,%204)%22%20style=%22w%22%3E4%20x%204%3C/button%3E%3Cbutton%20onclick=%22start(4,%205)%22%3E4%20x%205%3C/button%3E%3Cbutton%20onclick=%22start(5,%206)%22%3E5%20x%206%3C/button%3E%3Cbutton%20onclick=%22start(6,%206)%22%3E6%20x%206%3C/button%3E%3C/center%3E%60);%0A%7D%0A%0A%0Afunction%20start(r,l)%20%7B%0A%20%20%20%20//Timer%20and%20moves%0A%20%20%20%20min=0,%20sec=0,%20moves=0;%0A%20%20%20%20$(%22#time%22).html(%22Time:%2000:00%22);%0A%20%20%20%20$(%22#moves%22).html(%22Moves:%200%22);%0A%20%20%20%20time%20=%20setInterval(function()%20%7B%0A%20%20%20%20%20%20sec++;%0A%20%20%20%20%20%20if(sec==60)%20%7B%0A%20%20%20%20%20%20%20%20%20%20min++;%20sec=0;%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20if(sec%3C10)%20%0A%20%20%20%20%20%20%20%20%20%20$(%22#time%22).html(%22Time:%200%22+min+%22:0%22+sec);%0A%20%20%20%20%20%20else%20%0A%20%20%20%20%20%20%20%20$(%22#time%22).html(%22Time:%200%22+min+%22:%22+sec);%0A%20%20%20%20%7D,%201000);%0A%20%20%20%20rem=r*l/2,%20noItems=rem;%0A%20%20%20%20mode%20=%20r+%22x%22+l;%0A%20%20%20%20//Generating%20item%20array%20and%20shuffling%20it%0A%20%20%20%20var%20items%20=%20%5B%5D;%0A%20%20%20%20for%20(var%20i=0;i%3CnoItems;i++)%0A%20%20%20%20%20%20%20%20items.push(em%5Bi%5D);%0A%20%20%20%20for%20(var%20i=0;i%3CnoItems;i++)%0A%20%20%20%20%20%20%20%20items.push(em%5Bi%5D);%0A%20%20%20%20var%20tmp,%20c,%20p%20=%20items.length;%0A%20%20%20%20if(p)%20while(--p)%20%7B%0A%20%20%20%20%20%20%20%20c%20=%20Math.floor(Math.random()%20*%20(p%20+%201));%0A%20%20%20%20%20%20%20%20tmp%20=%20items%5Bc%5D;%0A%20%20%20%20%20%20%20%20items%5Bc%5D%20=%20items%5Bp%5D;%0A%20%20%20%20%20%20%20%20items%5Bp%5D%20=%20tmp;%0A%20%20%20%20%7D%0A%20%20%20%20%0A%20%20%20%20%0A%20%20%20%20$(%22table%22).html(%22%22);%0A%20%20%20%20var%20n=1;%0A%20%20%20%20for%20(var%20i%20=%201;i%3C=r;i++)%20%7B%0A%20%20%20%20%20%20%20%20$(%22table%22).append(%22%3Ctr%3E%22);%0A%20%20%20%20%20%20%20%20for%20(var%20j%20=%201;j%3C=l;j++)%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20$(%22table%22).append(%60%3Ctd%20i$*$d='$%7Bn%7D'%20onclick=%22change($%7Bn%7D)%22%3E%3Cdiv%20class='inner'%3E%3Cdiv%20class='front'%3E%3C/div%3E%3Cdiv%20class='back'%3E%3Cp%3E$%7Bitems%5Bn-1%5D%7D%3C/p%3E%3C/div%3E%3C/div%3E%3C/td%3E%60);%0A%20%20%20%20%20%20%20%20%20%20%20n++;%0A%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20$(%22table%22).append(%22%3C/tr%3E%22);%0A%20%20%20%20%7D%0A%20%20%20%20%0A%20%20%20%20%0A%20%20%20%20$(%22#ol%22).fadeOut(500);%0A%7D%0A%0A%0Afunction%20change(x)%20%7B%0A%20%20%0A%20%20let%20i%20=%20%22#%22+x+%22%20.inner%22;%0A%20%20let%20f%20=%20%22#%22+x+%22%20.inner%20.front%22;%0A%20%20let%20b%20=%20%22#%22+x+%22%20.inner%20.back%22;%0A%20%20%0A%20%20%20%0A%20%20if%20(turn==2%20%7C%7C%20$(i).attr(%22flip%22)==%22block%22%20%7C%7C%20ppID==x)%20%7B%7D%0A%20%20%0A%20%20%0A%20%20else%20%7B%0A%20%20%20%20$(i).css(t,%20flip);%0A%20%20%20%20if%20(turn==1)%20%7B%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20turn=2;%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20if%20(pre!=$(b).text())%20%7B%0A%20%20%20%20%20%20%20%20%20setTimeout(function()%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20$(pID).css(t,%20flipBack);%0A%20%20%20%20%20%20%20%20%20%20%20%20$(i).css(t,%20flipBack);%0A%20%20%20%20%20%20%20%20%20%20%20%20ppID=0;%0A%20%20%20%20%20%20%20%20%20%7D,1000);%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20else%20%7B%0A%20%20%20%20%20%20%20%20%20%20rem--;%0A%20%20%20%20%20%20%20%20%20%20$(i).attr(%22flip%22,%20%22block%22);%0A%20%20%20%20%20%20%20%20%20%20$(pID).attr(%22flip%22,%20%22block%22);%0A%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20setTimeout(function()%20%7B%0A%20%20%20%20%20%20%20%20%20turn=0;%0A%20%20%20%20%20%20%20%20%20%0A%20%20%20%20%20%20%20%20%20moves++;%0A%20%20%20%20%20%20%20%20%20$(%22#moves%22).html(%22Moves:%20%22+moves);%0A%20%20%20%20%20%20%7D,1150);%0A%20%20%20%20%20%20%0A%20%20%20%20%7D%0A%20%20%20%20else%20%7B%0A%20%20%20%20%20%20pre%20=%20$(b).text();%0A%20%20%20%20%20%20ppID%20=%20x;%0A%20%20%20%20%20%20pID%20=%20%22#%22+x+%22%20.inner%22;%0A%20%20%20%20%20%20turn=1;%0A%20%20%20%20%7D%0A%20%20%20%20%0A%20%20%20%20%0A%20%20%20%20if%20(rem==0)%20%7B%0A%20%20%20%20%20%20%20%20%20%20clearInterval(time);%0A%20%20%20%20%20%20%20%20%20%20if%20(min==0)%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20time%20=%20%60$%7Bsec%7D%20seconds%60;%0A%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20else%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20time%20=%20%60$%7Bmin%7D%20minute(s)%20and%20$%7Bsec%7D%20second(s)%60;%0A%20%20%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%20%20%20%20setTimeout(function()%20%7B%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20$(%22#ol%22).html(%60%3Ccenter%3E%3Cdiv%20i$*$d=%22iol%22%3E%3Ch2%3ECongrats!%3C/h2%3E%3Cp%20style=%22font-size:23px;padding:10px;%22%3EYou%20completed%20the%20$%7Bmode%7D%20mode%20in%20$%7Bmoves%7D%20moves.%20It%20took%20you%20$%7Btime%7D.%3C/p%3E%3Cp%20style=%22font-size:18px%22%3EComment%20Your%20Score!%3Cbr/%3EPlay%20Again%20?%3C/p%3E%3Cbutton%20onclick=%22start(3,%204)%22%3E3%20x%204%3C/button%3E%20%3Cbutton%20onclick=%22start(4,%204)%22%20style=%22w%22%3E4%20x%204%3C/button%3E%3Cbutton%20onclick=%22start(4,%205)%22%3E4%20x%205%3C/button%3E%3Cbutton%20onclick=%22start(5,%206)%22%3E5%20x%206%3C/button%3E%3Cbutton%20onclick=%22start(6,%206)%22%3E6%20x%206%3C/button%3E%3C/div%3E%3C/center%3E%60);%0A%20%20%20%20%20%20%20%20%20%20%20%20%20%20$(%22#ol%22).fadeIn(750);%0A%20%20%20%20%20%20%20%20%20%20%7D,%201500);%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D">Click here to play game!</a></h1></br>
    
<img src="https://drive.google.com/thumbnail?id=1zlQS0sBqGLn_pHhmHhWXoJWeYrn5ahcF"  width="1343" height="601"></br>
<img src="https://drive.google.com/thumbnail?id=1IANnd_t2kBpBP2iX09tmVvIRDilPjYJZ"  width="1343" height="601"></br>  
<img src="https://drive.google.com/thumbnail?id=1X-f5MTvHyGBJSafWo-Gd6WARdHadrRkA"  width="1343" height="601"></p>

  
</body>
 
</html>
