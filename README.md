# GoodBye
My Final Hello to MAQ
<!DOCTYPE html>
<html>
<head>
  <script src="//code.jquery.com/jquery-1.9.1.min.js"></script>
  <script src="http://mbraak.github.io/jqTree/tree.jquery.js"></script>
  <link rel="stylesheet" href="http://mbraak.github.io/jqTree/jqtree.css" />
  <link href='http://fonts.googleapis.com/css?family=Open+Sans' rel='stylesheet' type='text/css'>
  <meta charset="utf-8">
<!--
Created using JS Bin
http://jsbin.com

Copyright (c) 2015 by khagesh (http://jsbin.com/qevaq/78/edit)

Released under the MIT license: http://jsbin.mit-license.org
-->
<meta name="robots" content="noindex">
  <title>Long live everyone</title>

<style id="jsbin-css">
body {
  font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;  
}

#MAQJourney {
  min-width: 300px;
  max-width: 430px;
  font-family: inherit;
  display: inline-block;
  font-size: 1.2em;
}

.details {
  display: inline-block;
  margin-left: 50px;
  font-family: inherit;
  margin-top: 20px;
  min-width: 400px;
  max-width: 650px;
  vertical-align: top;
  font-size: 1.2em;
  position: fixed;
}

.jqtree_common.jqtree-toggler.jqtree-closed {
  font-size: 1.2em;
}

.jqtree_common.jqtree-toggler {
  font-size: 1.3em;
}
</style>
</head>
<body>
  <div>
    <div id="MAQJourney"></div>
    <div class="details"></div>
  </div>
<script>
var data = [
    {
        label: 'MAQ Journey',
        children: [
            { 
              label: 'Bootcamp: Begining of the begining',
              children: [
                {
                  label: 'Bootcamp',
                  value: 'Place where everyone in entire company shares same pain and create stories for life. You all know how much a bootcamp means to everyone and for me too it was no exception. Whole night working, sleeping on Yoga mats, playing on XBox, some anklets sound for many days(guthla :P), dard ho raha hai (Gopala :P), haath geeley hai terey (shishir), multi-threading not changing image on UI (name cannot be written), everything is distributed system (there was always one question related to distributed system, even if it is a SQL functions session :D), sleeping and snorting at last chairs, kya chikna ladka hai to some censored dance performance, randomly asking questions, discussing about every technology and in the end absuing all microsoft technologies, IE hater to work only in IE (:D), pet names cermony, there is a lot more to share and just thinking about that time brings back smile to my face and wants to say to everyone in my Bootcamp that THANK YOU VERY MUCH. YOU GUYS ARE AWESOME!'
                },
                {
                  label: 'Abhishek S',
                  value: "You are one of the most talented and yet down to earth great person. There are very few people like you in this world. I have always appreciated you. And my boy you are so popular among girls, jealous of you :P :P. I hope someday i would get a chance to work with you. My best wishes are always with you."
                },
                {
                  label: 'Asif',
                  value: "Oh boy, how much we have abused microsoft technologies and yet only you did what you wanted :D. An awesome learner and always active person. You have got too much energy for everything. I want to learn how to blow a whistle without any gesture. Still remember all that fun of Bootcamp. All the best.",
                },
                {
                  label: 'Akhila',
                  value: 'One of the most dedicated person i have seen. Your bootcamp persentation demos were awesome and luckily and i got chance to work with you and found that you did not change a single even after so many months of bootcamp, still same dedication and hard work. Your soft spoken personality is too good. My best wishes are always with you. If i would like to name opposite for Neha tyagi, then that will be you :D :D. I am going to get beaten soon, pray for my safety :D'
                },
                {
                  label: 'Chirag',
                  value: 'Cool dude :). Mast singer. Most of the things about you are just so cool. Keep rocking everywhere. All the best.'
                },
                {
                  label: 'Chandu',
                  value: "singing hindi songs, driving bike in style. You got cool and carefree personality. Don't give up, you are doing an awesome work, keep going boy. All the best!"
                },
                {
                  label: 'Dinesh',
                  value: 'Hey DC, i miss you sometimes. If you ever feel like establishing our brand. I am all up for it :D. I am sure you are doing very well. Enjoy and all the best.'
                },
                {
                  label: 'Geetha',
                  value: 'It was for a very short time that i got to work with you, but it was more than enough to tell that you are extermyl dedicated and hardworking person. I admire your spirit to learn. Keep working hard and i am sure within no time you will reach heights. Good luck :)'
                },
                {
                  label: 'Jalandhar',
                  value: 'Hey JP, another extra hard working guy from my bootcamp. I am pretty much sure the number of hours you have worked can give you an experience of 6 years easily :D. I want to learn how to dive in water and that flip thing in water. You too are awesome keep rocking.'
                },
                {
                  label: 'Kezia',
                  value: 'Never talked to me. I always wanted to start conversation and you were always like "Ok Khagesh, bye!". All i used to say was "Hey crazia how are you?" :P. Nevertheless, congratulations and all the best.'
                },
                {
                  label: 'Kurumoorthy',
                  value: "Guru your smile is too good and boy you are a fighter. I still want to know your story in detail. May you should write a novel about that :D. You can achieve all what you desire. All the best Guru. "
                },
                {
                  label: 'Neha L',
                  value: 'My Telugu trainer and you have not yet invited me to your home for those parathas that you always kept promising me. you have not yet given me a single ride in that car :P. Good luck :)'
                },
                {
                  label: 'Naresh',
                  value: 'Yo NRI, now you have to shoulder all the responsibility of MAQ :P as you have done up till now. Good luck man.'
                },
                {
                  label: 'Pramod',
                  value: 'Amma Pramodu :D. One of my bootcamp guy with whom i have worked for more than 2 years. And let me tell you that i have seen you growing so much in every aspect. You are the person that can learn anything be it backend, frontend, anyend. You know about everything that happens in company, going to happen in company, goes around in Hyderabad :P. Extremly dedicated and hardworker, you just him any kind of work and he will make sure to get it done. He is favourite to everyone and to make sure he remains favourite, he has 5 hours window as well :P :D. Jokes apart, you have your own path that you have created and you will definitely make it work right. All the very very Best Pramod.'
                },
                {
                  label: 'Pavani',
                  value: 'Hey Pavani. Everyday greeting you with exact same line and asking exact same question that you after seeing me used to tell me everything without even asking :D :D. You got so many responsibilities still you have taken time for your personal growth and career growth. Good luck :)'
                },
                {
                  label: 'Rambabu',
                  value: 'Ahh champ in MAQ. After RA and RC there is only RY. Please publish your book "What i did not learn in SharePoint". I am sure it will huge hit :D :D. One of the coolest guy who can make you laugh in any serious situation. I have enjoyed a hell lot chatting with you and sitting beside you. You are the only person in MAQ who can scold a person and yet that person is laughing or smiling. you are way above our level. Very soon you are going to be counted as top executvies and people will take coaching classes from you on topic "How to be cool" :P. Uptill now when people used to say there is some "R" letter connection in MAQ, i never believed that. But you my boy have made it true. Thanks for all the good time and help and everything. All the very very best RY.'
                },
                {
                  label: 'Shishir',
                  value: 'Merey haath abhe geeley nahi hai be. All the best!'
                },
                {
                  label: 'Sindhu',
                  value: 'Guthla the abusing girl. Everytime i hear something from you is either an abuse or a curse :P and i do not know why :P. And you should see yourself while you are crossing a road. I guess you can stop traffic just by shouting in the middle of the road instead of crossing it. Congratulations and all the best.'
                },
                {
                  label: 'Srikanth D',
                  value: "The sharpest brain. Perfect example of all good things in small packages. You are always calm and cool and man i have learnt so many things from you. how to use brain, how to type, how to keep focus everywhere. You can learn anything anytime. I wish to work with you and we could have been very good friends if i had been in college with you :D. Give me recording of your laugh along with Rambabus' as well :D ;)"
                },
                {
                  label: 'Srikanth Y',
                  value: 'Anna! Amazingly talented and cool person. All the very best!'
                },
                {
                  label: 'Venkateswar T',
                  value: 'Venky. You are the one person who always talks everything straight and when you put forward your point it is always backed with strong examples. I have learnt this from you. Keep rocking and keep rising. All the best boy;)'
                },
                {
                  label: 'Vibhuti',
                  value: 'Bharpoor talented. Mausi ladka heera hai heera. Aisey talent ka toh ladka roj kulla karta hai. Apna heera, apney tarikey se kaam karna mast mauj wala ladka hai. Aur kaam toh koi bhee de do aur jab bolo tab tak khatam ho jayega chahey jugaad koi bhee ho :P :D. Aur area koi bhee ho bhai ka talent har jagah chalta hai chahe subha tayar ho kar aana ho ya party (dusri wali) ho ya koi gyaan dena ho ladka hamesha no.1 rehta hai. Jug jug jiyo laala. :D'
                } 
              ]
            },
            { 
              label: 'Projects: Shadow teacher',
              children: [
                {
                  label: "CIBI",
                  children: [
                    {
                      label: 'Sunil G',
                      value: 'Jahan Sunil g jaatey hai bahar toh bas wahin aati hai. Sunil g pass banva hua hai park ka aur khoob maze kaatey ho. Aur GVK waley toh discount deney lagey hongey aapko :D. Thank you being my mentor for personal and professional growth. You are the person who taught me to say NO. You told me to always do the best things in right way. You can single handedly deliver any backend work or project. Neve got chance to work with you under your technical area, but i know how high everyone thinks of you :). Ek baat aur kasam se tirupati aur nayak bhaiyia ko lagta hoga ki aap unki bhee job na khaa jaao raat bhar toh office mein rehtey they :P. Office ki chaabi le rakhi thi aapney ek alag se :P'
                    },
                    {
                      label: 'Naveen Ki',
                      value: "Pillar of sunil g. Abe tu pehle kitna tabeley mein jata tha fir chhoda kyun udhar se re. Bhai abhe bhee tera weight utna hi lagta hai mujhe :P :P. Inheriter of the will left by Sunil g, diggi and Anurag banka :P. Now you can not have those dreams because you don't even sleep :P. You can work continously for 3-4 without any sleep, awesome stamina and cool technical and domain skills. All those who have worked with you can not forget your amazing sense of humour, your opinion and decision making power. You are too good :)"
                    },
                    {
                      label: 'Nikhil',
                      value: 'Nikhil bhai mast lagey raho (y). I have enjoyed and learnt a lot working with you. Thank you for mentoring me. All the very best.'
                    },
                    {
                      label: 'Varun',
                      value: 'All the very best and we shall continue our Anime watching competition. Thank you for all the advice and mentoring me :). It was fun working with you for me.'
                    },
                    {
                      label: 'Karishma',
                      value: 'You have got a lovely smile. Just keep smiling and all the best.'
                    }
                  ]
                },
                {
                  label: "FSABI",
                  children:[
                    {
                      label: 'Rohit Khatri',
                      value: "For me saga of any backend project cannot start without this awesome man. You are one the coolest and awesome Redmond POCs i have worked so far. I always wonder what is it in this world that you don't know. One incident i would like to share with all others, in one of our calls Barbieto (Product Owner) had created one task and asigned to herself, then one day in our weekly sync up call she asked what this task is for. Then Rohit was the one told Barbieto that this task is related to this thing and you had created it and assigned to yourself. :D :D After that day in India we always say that Rohit tumhey kuchh bhee samjha sakta hai, kuchh bhee bata sakta hai, aur kuchh bhee kar sakta hai. Hats off to your dedication and knowledge."
                    },
                    {
                      label: 'Venkatesh Appala',
                      value: 'You are the person who get things done. If someone wants to get any of his work done perfectly you are the perfect choice. You will try to find every corner case of everything and will try to solve it as well. You have been a great help. Thank you for not minding me sleeping all throughout the meetings and discssions :D and all the very best.'
                    },
                    {
                      label: 'Hussain',
                      value: 'Babu hussainu. Mahesh  babu of Telanga superstar of FSABI and Telangana. You are too much dedicated and hard worker. Good luck!'
                    },
                    {
                      label: 'Aditya',
                      value: 'Yeh apna champ ladka. He can push everyone beyond their limits. He is the leader. He has awesome talent and dedciation to make everything work and he can learn anything. You take few things too seriously :D. Take everything(politics, personal etc.) light (except work :)). Tu toh Hamesha ab merey saath rahega :P'
                    },
                    {
                      label: 'Anurag D',
                      value: 'yaar kitney naam hai terey. Talented, LK, Super talented. Aur hero hai re tu Dark, tall and Handsome :P. Bhai ladka bahut saarey breakfast karta hai aur shayad 2 baar lunch karta hai :D. Apart from your talent in every sphere, never seen you too much angry and that is one good thing. Keep your focus, as i said you are talented you can learn and work on anything just give yourself a little time. All the best.'
                    },
                    {
                      label: 'Surbhi',
                      value: 'Chhota bomb bada dhamaka. encylopedia of FSABI :P. You are very dedicated and hard working person. And now you have learnt to say no as well. Great going when i was your experience i had nothing like that sort of technical command or professional skills, but you are managing all of them quite gracefully. Keep up the awesome work. All the Best!!'
                    },
                    {
                      label: 'Siddhant',
                      value: "Bhai achha hua mene resign kar diya varna toh pakka hum log company se nikaley jaaney waley they :D :D. (maattey maattey). Kam kaam honey ka kabhe kabhe bahut nuksaan hota hai be. Aur achha hua Brijesh ko pata nahi chala ki kya chal raha tha :D. Another guy who share same sleeping habit as me and who can sleep through entire QPU at front seat :D. Remember what we discussed and let me know your thoughts :P :P. You have the potential to lead any team from front (take it in positive way :P) and you can do wonders with your skills. All the best."
                    },
                    {
                      label: 'Brijesh',
                      value: 'I always used to stand up and see from one end of the ODC and see who is laughing at then other end of ODC, when i joined my project and it was always you. Even if nobody is laughing in entire ODC, then after they hear you laugh everybody used to laugh and i was like what happened now. You maintained a strange curiosity as to what kind of joke a guy can laugh this much :D. Then we both meet in same team and i got to know that all you need to laugh is just another person trying to crack a joke (not even cracked yet :D) :D :D. And i feel that i come next to you when it comes to laugh on anything. You are extremly talented and yet down to earth and never ever shows off anything. You take care of all your team mates and thanks for all the parties and extra budgets that set out for us. All the best.'
                    },
                    {
                      label: 'Rahul Pal',
                      value: 'Another guy with awesome skills and let go attitude. You are the one who is in my opinion kind of lazy for very long things and that is is the best part you get things done in shortest way. Also, you are a blunt person who cares for none when wants to express his feelings. In my opinion this is cool :). So fear not consider none. Do bindass and you are cool. All the best buoy.'
                    },
                    {
                      label: 'Vishal',
                      value: 'Bahut churan deta hai bhai:). All the best, if you put all your efforts at one place for sometime you can do magic work. But that is just my suggestion, do what you love to do. All the best.'
                    },
                    {
                      label: 'Arpit',
                      value: 'Bhai gardan ghumana chhod de. Kam se kam aamney saamney toh mat ghumaya kar :P. Hard working person and you have improved a lot since the begining of bootcamp. Good luck.'
                    },
                    {
                      label: 'Raja',
                      value: 'Raja day aaja tera bday manayengey :). Extremly dedicated and hard working person you want to learn many things and you do just keep going like this and you will do great work. All the best.'
                    },
                    {
                      label: 'Hitesh',
                      value: 'Bhai ab kya batau tu mera POC tha. tune mujhe bahut sikhaya hai aur mene agar kuchh kiya bhee nahi toh tu tha sab karney ke liye. Bhagvaan karey aisa POC har kisi ko miley. Pehli baar company se bunk maar ke movie dekhney gaye :D :D. terey saath beth kar khaney ka maaza aata tha kyunki tu le kar aata hai bahut saara :D. Awesome person with amazing sense of humour, may be first user of 5 hour window :P :P. You are one of the rarest kind of person on earth. Tu itna down to earth hai ki tu chalta bhee reng reng kar hai :D :D. Everyone who has worked with you even for a little time, you are a good friend with all of them. Plan kartey hai kahin ghumney chalney ka jaldi se ;)'
                    }
                  ]
                },
                {
                  label:'Design portfolio',
                  children: [
                    {
                      label: 'Avantika',
                      value: 'thanks for medicine :). Keep working and exploring. You are going very good. Aur koi na miley toh khud ghumney nikal jaa. Next time sab chalengey fir saath mein ;)'
                    },
                    {
                      label: 'Ashutosh',
                      value: 'Dekhna mein bahut seedha lagta hai bhai tu, but hai nahi. Talented and hardworking person. All the best'
                    },
                    {
                      label: 'Lav',
                      value: 'You are hard working but you need to empty your cup for small things :). Keep exploring new things and learn new technologies on your own. All the best.'
                    },
                    {
                      label: 'Lofty',
                      value: 'Another person with whom i share almost same sleeping habit. Snorting during a call by sitting very near to speaker phone :D :D. You are talented and yes do not hesitate to ask any question. Keep up the good work. You are good human too. :)'
                    },
                    {
                      label: 'Shipra',
                      value: 'POC of Design portfolio. Redmond team always wants to sync up with Shipra :D. You are intelligent and very eager to learn new things. Keep up awesome work. You are doing wonders:)'
                    },
                    {
                      label: 'Kanika',
                      value: 'Although you left MAQ little too early, but i am sure you will create another good path for your success. All the very best.'
                    },
                    {
                      label: 'Deepanjali',
                      value: 'Thanks deepanjali for everything. You are one of the most nervous and same time cool POC from Redmond :). Take care and all the very best. BTW you can be very good QA as well :D :D'
                    }
                  ]
                }
              ]
            },
            { 
              label: 'Friends: Life changers',
              children: [
                { 
                  label: 'Pranshu',
                  value: "There is so much to tell about you and to tell you i can't begin to list everything. You are one of my ideals and i have learnt so many things from you. Being with you is always so much fun and laugh. Now i don't even remember how many times we have been scolded by people to laugh in public area and literally insulted and forced to keep quiet. You respect and care about others way too much. And you have to give so many parties to me that i can't even count them now. You better finish all those early :P. You can achieve any height you want in your career. You want to learn everything in right way. I would definitely like to work with you someday :)"
                },
                { 
                  label: 'Gopala: Our bootcamp topper',
                  value: "Bhai kitni languages aati hai tujhe. aur sab languages mein har gandi cheej tujhe pata hai :P. I miss those lunch table talks and your silent yet awesome jokes, those teeth breaking laddu, lets plan some trip again. Yaad hai wo dard ho raha hai wali kahani :P. You just give this guy a hint about anything and he will develop anything out of it be it technical, be it a joke or a situation, you are master in everything. Very rarely i have seen you loose temper and then also you smile while complaining :D. I forgot so many girls left MAQ because of you :P. Aur kitni baatein karta hai be tu whats app par (sirf ladkiyon se :D) :P. Always want to give best and you deliver in every aspect of life. how can i forget those trips and parties that you plan for your family (i still can't forget that shadi ke laddu khilaney wala video) and for us. You crack joke with serious face and many people actually believes that is not a joke and on top of that you don't want to clarify as well that was a joke :D :D. Bhai tu ghar toh abhe tak nahi le kar gaya hai kab le kar jaayega aur chal chaltey hai kahin ghumney :D"
                },
                { 
                  label: 'Neha T',
                  value: "You are one of those reasons which kept me surviving in Hyderabad. Just because of your food and blunt advice i am still surviving in Hyderabad. Hats off to you tyagi. You are always with your friends and you do almost everything for your friends and family. I have never been much help to you, but i still try to do little things. You are simple and straightforward and that is the best thing about you. You know another best thing about you is that you never regret anything and always thinks what is done is right :D. Knowing same kind of enviroment and language it is too much fun to tease others about things that they don't know and silently make suspense of anyword (jhod, buunga, etc.). With all said you are always there for everyone and you are the one of the best friends i ever had. THANK YOU TYAGI :)"
                },
                { 
                  label: 'Faiz',
                  value: 'I wish i had been your college friend. We have invested too much time in Bootcamp to laugh and make joke that we could have done 4-5 assignments more in that time :D. You are rockstar and superstar of MAQ. Always smiling, and only person in MAQ who actually enjoys a hell lot :p :P. And i forgot, individually, we both have used approx 500 hours in just watching one piece and naruto and another 20-30 hours just discussing about them, damn i am going to miss all those conversations. Although i never got to drive your car but i have abused you a lot for purchasing a car, kaminey mujhe bhe leni thi car aur tune pehle le li saaley. Your after 9 PM timings are too busy and continously changing targets are too much :D. All the very best Faiz. I hope we will keep in touch always.<br /><br />PS: kuchh jokes ladko ko bhee bhej diya kar :P'
                },
                { 
                  label: 'Pooja Mam',
                  value: 'Pooja mam agar aap hi na hotey toh bhukey bachho ko khana kaun khilata. Wo bhee ek dum mast wala :D. Never seen you angry. Your laugh is too good. I have enjoyed a lot with you and i miss that food and those times.'
                },
                { 
                  label: 'Ravi T',
                  value: 'My first best friend in MAQ. Only we know how we have spent Bootcamp in MAQ along with hostel life :). You went for a marriage and did not come back :P. And then you again came back and went again :P. However, i know i have enjoyed a whole lot with you and remember every friday night and all other times we have laughed a lot. I am sorry i was not able to do much for you. You hold a special place for me. Thank you for being in my life janeman.'
                },
                { 
                  label: 'Rajiv',
                  value: 'These past years i have enjoyed a lot with you. I am sorry if i have hurted you and even if i did that would not have been intentional. Thanks for being a part of my life. All the very best Rajiv.'
                }
              ]
            },
            { 
              label: 'Mentors: Strict teachers',
              children: [
                {
                  label: 'Megha',
                  value: "The awesome and coolest manager who likes to code more than anything. I still remember my very first one on one. We were not having any discussion about problems or personal things all we discussed was technology and you said 'aaney de aaney de' :D. You came to Hyderabad and i was like oh new person from Mumbai, then sunil g told me 'abe manager hai wo apney project ki' :o :o. And then i thought might be top college and then he told ki 4 years se jayada ka exp hai .. mene puchha ghar walo ko koi problem nahi hai toh boley shaadi ho gayi hai unki... bas from that moment on you are the inspiration and ideal for me. Thank you for bearing all my nuisances and delayes and bugs and what not. All the very best you are best mentor a person can get. :)"
                },
                {
                  label: 'Ronojoy',
                  value: "I learnt a lot from you. How to negotiate, how to make others listen to you, how to bargain, how to keep everything in check. Thank you for teaching me some important lessons of the life."
                },
                {
                  label: 'Lokenath',
                  value: "Few words that comes to mind after you hear this name is 'COOL, CHILL, FRIEND'. You will never ever feel that you are talking to your manager and he understands everthing so perfectly and is just awesome in what he does. Even if he can not produce an answer right away, he will find it for hours and will definitely tell you what should be right way. He can tell you straight to your face if he is not liking something and that also in a manner that you will feel encouraged. All the very best and good luck!:)"
                }
              ]
            },
            {
              label:'Policies: not every single of them is wrong :)',
              children: [
                {
                  label: "8:45",
                  value: "For me it was too hard to accomplish this and many times i was embarassed becuase of this as i was literally running on stairs, on road, driving too rash many times. If this check in time would not have been here i would be willing to work dedicatedly to complete a project. But then in the evening i think that i have to come early tomorrow so just leave. I used to come by my call timings and happily work on project, but this policy (just that max half an hour) changed so much for me. I know this is all well and good policy but everyone is different, they have their own workstyle and different work output at different times. If the slack because of their work style they are never going to complain about it."
                },
                {
                  label: "Others",
                  value: "For my fellow MAQ people, there are lot of good things about MAQ, you will learn a lot, you will grow exponentially in terms of personal and professional growth. Quit MAQ only if you know what exactly you are trying to do. think about bigger pictures first and then see if it is worth yet to leave MAQ."
                }
              ]
            },
          {
            label: 'Important people',
            value: 'Big thanks to Adarsh, Girish, Kapil and Ankush for giving me this opportunity.<br /><br /> I am really sorry if i forget someone, i am just running out of time :). All the very best to Abhishek Mahapatro, Ankit kushwaha, Akshay,  Anup, Ankita, Aquil, Ayush, Charu, Chintan, keshav g, Mullai, Neha thakur, Narendra, Niranjan, Raghvendra B, Sachin S(the hero), Srinivas, Sreedhar, Sarthank, Saswat, Sumit S, Srikumar I, Suresh, Vaibhav and to all of you whom i have missed. Pardon me :)'
          },
          {
            label: 'Awesome HR, Admin team and IT team',
            value: 'Big thanks to Neetu (the best), Anusha, Neeraja, Baljeet(super awesome person and super cool, i still doubt my patience capability when i see you answering same question to hundereds of people in a day.), Rohit, Anish, Anurag, Babesh, Aniket. Whenevr i walk upto to you guys i feel like going to a good friend to ask for help. Thank you :)'
          }
        ]
    },
    {
        label: 'Contact: Please keep in touch',
        children: [
          { label: 'Mobile no.: +919177748454', value: '+919177748454' },
          { label: 'Gmail: khageshhiet@gmail.com', value: 'khageshhiet@gmail.com' },
          { label: 'Facebook', value: '<a href="https://www.facebook.com/khageshsharma">https://www.facebook.com/khageshsharma</a>' },
          { label: 'Twitter', value: '<a href="https://twitter.com/khagesh17">https://twitter.com/khagesh17</a>' },
          { label: 'Linkedin', value: '<a href="https://www.linkedin.com/profile/view?id=83577927">https://www.linkedin.com/profile/view?id=83577927</a>' }
        ]
    }
];



$(function() {
    var domDetails = $(".details");
    $('#MAQJourney').tree({
        data: data,
        closedIcon: '+',
        openedIcon: '-',
        autoOpen: false,
        keyboardSupport: true,
        onCanSelectNode: function(node) {
        if (node.children.length === 0) {
            // Nodes without children can be selected
            return true;
        }
        else {
            // Nodes with children cannot be selected
            return false;
        }
    }
    });
  
    $('#MAQJourney').on('tree.click', function(event){
      // get the node value from the data
      var clickedNode = event.node;
      domDetails.html(clickedNode.value);
    });
});
</script>
<script src="http://static.jsbin.com/js/render/edit.js?3.25.14"></script>
<script>jsbinShowEdit && jsbinShowEdit({"static":"http://static.jsbin.com","root":"http://jsbin.com"});</script>

<script>
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//www.google-analytics.com/analytics.js','ga');
ga('create', 'UA-1656750-34', 'jsbin.com');
ga('require', 'linkid', 'linkid.js');
ga('require', 'displayfeatures');
ga('send', 'pageview');

</script>

</body>
</html>
