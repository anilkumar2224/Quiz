var science=[
    {
        question:"An astronaut in outer space will observe sky as",
        options:['White','Black','Blue','Red'],
        answer:'B',
        size:0

    },
    {
        question:"In a study, which cells are found in COVID-19 patients 'bode well' for long term immunity ?",
        options:['P-cell','D-cell','T-cell','Endothelial Cells'],
        answer:'C',
        size:1

    },
    {
        question:"What is the first living animal on earth ?",
        options:['Comb Jelly','Horseshoe Crab','Coelacanth','Lamprey'],
        answer:'A',
        size:0

    },
    {
        question:"What is car-pooling",
        options:['Air pollution due to car','Intensive whasing of car','Sharing a ride ','None'],
        answer:'C',
        size:0

    },
    {
        question:"Which is the most abundant hydrocarbon in the atmosphere?",
        options:['Methane','Carbonyl sulphide','Ethane','None'],
        answer:'A',
        size:0

    }
];
var maths=[
    {
        question:"How many holes does a Straw have ?",
        options:['0 holes','1 hole','2 holes','Infinity'],
        answer:'B',
        size:0

    },
    {
        question:"If you choose an answer to this question at random, what is the chance you will be correct ?",
        options:['25%','50%','0%','25%'],
        answer:'C',
        size:0
    },
    {
        question:"3+5=16 4+7=30 1+1=?",
        options:['3','0','-12','2'],
        answer:'C',
        size:0
    },
    {
        question:"When does Fahrenheit=Celsius",
        options:['273','-40','100','0'],
        answer:'B',
        size:0
    },
    {
        question:"If a company has to give a holiday to all employees for the birthday of any employee, how many employees should a company hire ?",
        options:['362','364','365','either B or C'],
        answer:'D',
        size:1
    }

];
var coding=[
    {
        question:"Which is the first Internet search engine?",
        options:['Google','Archie','Altavista','WAIS'],
        answer:'B',
        size:0

    },
 
    {
        question:"A complete Binary Tree contains 15 nodes, then how many edges are there in the tree ?",
        options:['15','30','14','16'],
        answer:'C',
        size:1
    },
    {
        question:"What is the infix version of the following postfix expression... ?  12 + z 17 y + 42 * / + ",
        options:['x+12+z/17+y*42','x+12+z/((17+y)*42)','(x+12+z)/(17+y*42)','None'],
        answer:'B',
        size:1
    },
    {
        question:"Which of the following sorting algorithm is NOT stable ?",
        options:['Selection sort','Bubble sort','Merge sort','Tim sort'],
        answer:'A',
        size:0
    },
    {
        question:"To measure Time complexity of an algorithm Big O notation is used which:",
        options:['describes limiting behaviour of the function','characterises a function based on growth of function','upper bound on growth rate of the function','all of the mentioned'],
        answer:'D',
        size:2  
    }

];
var english=[
    {
        question:"Our country is spiritual country, theirs.....religious",
        options:['is','or','also','have'],
        answer:'A',
        size:0
    },
    {
        question:"Find the correct spelt word ",
        options:['Adventitious','Adventitous','Adventitus','Adventituous'],
        answer:'A',
        size:0
    },
    {
        question:"His appearance is unsmiling but ......",
        options:['his heart is full of compassion for others','he looks very serious on most occasions','people are afraid of him','he is uncompromising on matters of task performance'],
        answer:'A',
        size:2
        
    },
    {
        question:"It was him / who came / running / into the classroom.",
        options:['who came','It was him','running','no ERROR'],
        answer:'B',
        size:0
    },
    {
        question:"A hater of knowledge and learning:",
        options:['Bibliophile','Philologist','Misogynist','Misologist'],
        answer:'D',
        size:0
    }
];
var number=document.getElementById('number');
var start=document.getElementById('start');
var card=document.getElementById('q');
var next=document.getElementById('next');
var sdis=document.getElementById('score');
var restart=document.getElementById('restart');
var opt1=document.getElementById('opt1');
var opt2=document.getElementById('opt2');
var opt3=document.getElementById('opt3');
var opt4=document.getElementById('opt4');
var score=0;
var currentquestion=0;
var back=document.getElementById('back');
var bk=document.getElementById('bk');
var question=document.getElementById('question');
var id=0;
var myvar=0;
var countdown=30;
var down= document.getElementById('down')
var btn=document.getElementById('dbtn');
var s=document.getElementById('science');
var c=document.getElementById('coding');
var m=document.getElementById('maths');
var e=document.getElementById('english');
var selectType;
var first=document.getElementById('select');
var scorecard=document.getElementById('scorecard');
var userAnswers=[];
var startb=document.getElementById('startb');
var btn1=document.getElementById('dbtn1');
var timer=document.getElementById('timer');
var firework=document.getElementById('fw');
var bg=document.getElementById('bg');
var insta=document.getElementById('insta');
var b=document.getElementById('b');
var butt=document.getElementById('butt');
var clock=document.getElementById('clock');
var canva=document.getElementById('canvas1');

s.addEventListener('click',()=>{
    selectType=science;
    start.classList.remove('hide');
    insta.classList.remove('hide');
    first.classList.add('hide');
    bk.classList.add('hide');
    bk.classList.add('svg');
    canva.classList.add('hide');
    back.classList.remove('hide');
    back.classList.add('stt5');
});
m.addEventListener('click',()=>{
    selectType=maths;
    start.classList.remove('hide');
    insta.classList.remove('hide');
    first.classList.add('hide');
    bk.classList.add('hide');
    canva.classList.add('hide');
    bg.classList.add('svg');
    back.classList.remove('hide');
    back.classList.add('stt5');
});
c.addEventListener('click',()=>{
    selectType=coding;
    start.classList.remove('hide');
    insta.classList.remove('hide');
    first.classList.add('hide');
    bk.classList.add('hide');
    canva.classList.add('hide');
    bg.classList.add('svg');
    back.classList.remove('hide');
    back.classList.add('stt5');
});
e.addEventListener('click',()=>{
    selectType=english;
    start.classList.remove('hide');
    insta.classList.remove('hide');
    first.classList.add('hide');
    bk.classList.add('hide');
    canva.classList.add('hide');
    bg.classList.add('svg');
    back.classList.remove('hide');
    back.classList.add('stt5');
});

back.addEventListener('click',()=>{
    first.classList.remove('hide')
    start.classList.add('hide');
    insta.classList.add('hide');
    back.classList.add('hide');
    score=0;
    bg.classList.remove('firework');
    bg.classList.add('svg');
    scorecard.classList.add('hide');
    currentquestion=0;
    start.classList.add('hide');
    sdis.classList.add('hide');
    startb.classList.remove('stt3');
    start.innerText="start";
    firework.classList.add('hide');
    startb.classList.add('stt');
    bk.classList.remove('hide');
    canva.classList.remove('hide');
    butt.classList.add('hide');
});

btn.addEventListener('click',()=>{
    
    btn1.classList.remove('hide');
btn.classList.add('hide')
    down.classList.remove('hide');

});
btn1.addEventListener('click',()=>{
  
    
    btn1.classList.add('hide');
    btn.classList.remove('hide');
    down.classList.add('hide');
});
window.onclick = function(event) {
    if (!event.target.matches('.dbtnc')){
        btn1.classList.add('hide');
        btn.classList.remove('hide');
    down.classList.add('hide');
    }
};

 var timer=document.getElementById('timer');
start.addEventListener('click',()=>{
    back.classList.remove('stt5');
  back.classList.add('hide');
  bg.classList.remove('svg');
  userAnswers=[];
    score=0;
    bg.classList.remove('firework');
    firework.classList.add('hide');
    currentquestion=0;
    startb.classList.remove('stt');
    insta.classList.add('hide');
    start.classList.add('hide');
    card.classList.remove('hide');
    sdis.classList.add('hide');
    scorecard.classList.add('hide');
    window.clearTimeout(id);
    butt.classList.add('hide');
    loadQuestion(currentquestion);

});
var option;
function loadQuestion(qindex){
    if(qindex<selectType.length){
        timer.classList.remove('hide');
        clock.classList.remove('hide');
        timer.style.color='#000000';
        timer.innerText='Time Left 0:30';
        
     window.clearTimeout(id); 
     
    var q=selectType[qindex];
    if(q.size==1){
        card.style.height='450px';
    }
    else if(q.size==2){
        opt1.style.height='45px';
        opt2.style.height='45px';
        opt3.style.height='45px';
        opt4.style.height='45px';
        card.style.height='450px';
    }
    else{
        card.style.height='400px'; 
        opt1.style.height='35px';
        opt2.style.height='35px';
        opt3.style.height='35px';
        opt4.style.height='35px';
    }
    number.innerText=qindex+1+'.';
    question.textContent=q.question;
    opt1.textContent=q.options[0];
    opt2.textContent=q.options[1];
    opt3.textContent=q.options[2];
    opt4.textContent=q.options[3];
    start1();
   
   }
    else{
        window.clearTimeout(id);
        timer.classList.add('hide');
        clock.classList.add('hide');
        sdis.innerText='Score :  '+score;
        card.classList.add('hide');
        start.innerText="Restart";
        back.classList.remove('hide');
        sdis.classList.remove('hide');
        start.classList.remove('hide');
        startb.classList.add('stt3');
        scorecard.classList.remove('hide'); 
        butt.classList.remove('hide');
        next.innerText='SKIP';
        if(score>=4){  
        firework.classList.remove('hide');
        }
        bg.classList.add('firework');
        currentquestion++;
        butt.addEventListener('click',()=>{
            back.classList.add('hide');
            bg.classList.remove('svg');
            bg.classList.remove('firework');
            firework.classList.add('hide');
            index=0;
            startb.classList.remove('stt');
            insta.classList.add('hide');
            start.classList.add('hide');
            card.classList.remove('hide');
            sdis.classList.add('hide');
            scorecard.classList.add('hide');
            window.clearTimeout(id);
            butt.classList.add('hide');
             next.innerText='NEXT';
           index=0;
           showAnswer(); 

        });
        return;
    }
};
var index=0;
function showAnswer(){
    if(index<selectType.length){
        timer.classList.add('hide');
        clock.classList.add('hide');
     window.clearTimeout(id); 
     
    var q=selectType[index];
    if(q.size==1){
        card.style.height='450px';
    }
    else if(q.size==2){
        opt1.style.height='45px';
        opt2.style.height='45px';
        opt3.style.height='45px';
        opt4.style.height='45px';
        card.style.height='450px';
    }
    else{
        card.style.height='400px'; 
        opt1.style.height='35px';
        opt2.style.height='35px';
        opt3.style.height='35px';
        opt4.style.height='35px';
    }
    number.innerText=index+1+'.';
    question.textContent=q.question;
    opt1.textContent=q.options[0];
    opt2.textContent=q.options[1];
    opt3.textContent=q.options[2];
    opt4.textContent=q.options[3];

    if(q.answer=='A'){
        opt1.style.background="green";
        if(userAnswers[index]!='A'){
            
            if(userAnswers[index]=='B'){
                opt2.style.background="red";  
            }else if(userAnswers[index]=='C'){
                opt3.style.background="red";
            }
            else if(userAnswers[index]=='D'){
                opt4.style.background="red";
            }
        }
    }
    else if(q.answer=='B'){
        opt2.style.background="green";
        if(userAnswers[index]!='B'){
            if(userAnswers[index]=='A'){
                opt1.style.background="red";  
            }else if(userAnswers[index]=='C'){
                opt3.style.background="red";
            }
            else if(userAnswers[index]=='D'){
                opt4.style.background="red";
            }
        }
    }
    else if(q.answer=='C'){
        opt3.style.background="green";
        if(userAnswers[index]!='C'){
            if(userAnswers[index]=='A'){
                opt1.style.background="red";  
            }else if(userAnswers[index]=='B'){
                opt2.style.background="red";
            }
            else if(userAnswers[index]=='D'){
                opt4.style.background="red";
            }
        }
    }
    else if(q.answer=='D'){
        opt4.style.background="green";
        if(userAnswers[index]!='D'){
            if(userAnswers[index]=='B'){
                opt2.style.background="red";  
            }else if(userAnswers[index]=='C'){
                opt3.style.background="red";
            }
            else if(userAnswers[index]=='A'){
                opt1.style.background="red";
            }
        }
    }

   
   }
}


option=document.querySelectorAll('li button');
    
    
        option[0].addEventListener('click',()=>{
            if(currentquestion<=5 ){
            if(option[0].value==selectType[currentquestion].answer){
                ++score;
            }
            userAnswers.push(option[0].value);
            
           
                currentquestion++;
                loadQuestion(currentquestion);  
          
        }
            
                     
                     
              
          
        });
        option[1].addEventListener('click',()=>{
            if(currentquestion<=5){
            if(option[1].value==selectType[currentquestion].answer){
                ++score;
            }
            userAnswers.push(option[1].value);
          
        
            currentquestion++;
            loadQuestion(currentquestion);   
               
            }      
                    
            
          
        });
        option[2].addEventListener('click',()=>{
            if(currentquestion<=5){
            if(option[2].value==selectType[currentquestion].answer){
                ++score;
            }
            userAnswers.push(option[2].value);
           
          
            currentquestion++;
            loadQuestion(currentquestion);  
               
        }        
                     
              
          
        });
        option[3].addEventListener('click',()=>{
            if(currentquestion<=5){
            if(option[3].value==selectType[currentquestion].answer){
                ++score;
            }
            userAnswers.push(option[3].value);
           
         
            currentquestion++;
            loadQuestion(currentquestion);   
              
        }         
                     
             
          
        });
     
          
    
        next.addEventListener('click',()=>{
        if(currentquestion<=5 || index>=4){
            userAnswers.push(null);
            opt1.style.background="#626ee3";
                opt2.style.background="#626ee3";
                opt3.style.background="#626ee3";
                opt4.style.background="#626ee3";
               window.clearTimeout(id); 
               currentquestion++;
            loadQuestion(currentquestion); 
        }
            else{
                index++;
                opt1.style.background="#626ee3";
                opt2.style.background="#626ee3";
                opt3.style.background="#626ee3";
                opt4.style.background="#626ee3";
            showAnswer(index);
            }  
               
                 
           });
          
           function start1(){
            countdown=30;
       id= window.setInterval(()=>{
        
         
          countdown--;
          if(countdown==0){
            timer.style.color='#000000';
            clock.style.color='#000000';
            timer.innerText='Time Left 0:30';
            window.clearTimeout(id);
            currentquestion++;
            loadQuestion(currentquestion);  
          }else{
           if(countdown<=3){
               timer.style.color='red';
               clock.style.color='red';
           }else{
            timer.style.color='#000000';
            clock.style.color='#000000';
           }
           if(countdown<10)
            timer.innerText='Time Left 0:0'+countdown;
            else
            timer.innerText='Time Left 0:'+countdown;
             
          }
         
           },1000);
        };
    
        function draw() {
            var ctx =document.getElementById('canvas1').getContext('2d');
          if (canvas1.getContext) {
          
            
            ctx.beginPath();
           
            ctx.moveTo(75, 50);
             ctx.lineTo(25, 75);
             ctx.lineTo(75,100);
             ctx.lineTo(42,75);
           
            ctx.fill();
          
            
            ctx.beginPath();
            ctx.moveTo(85, 50);
             ctx.lineTo(135, 75);
             ctx.lineTo(85,100);
             ctx.lineTo(118,75);
            ctx.closePath();
            ctx.strokeStyle = 'rgb(0, ' + Math.floor(255 - 42.5 * 0) + ', ' + 
                                 Math.floor(255 - 42.5 * 0) + ')';
            ctx.stroke();
           
          
          }
          }
