const btnHamburger = document.querySelector('#btnHamburger')
const header = document.querySelector('.header');
const overlay = document.querySelector('.overlay')
const fadeElems = document.querySelectorAll('.has-fade');
const body = document.querySelector('body');


btnHamburger.addEventListener('click', ()=>{
    
    if(header.classList.contains('open')){
        header.classList.remove('open');
        fadeElems.forEach(x=>{
            x.classList.remove('fade-in');
            x.classList.add('fade-out');
        })
        overlay.classList.remove('fade-in');
        overlay.classList.add('fade-out');
        body.classList.remove('noscroll');
    } else {
        body.classList.add('noscroll');
        header.classList.add('open');
        fadeElems.forEach(x=>{
        x.classList.remove('fade-out');
        x.classList.add('fade-in');
        });
    }
})