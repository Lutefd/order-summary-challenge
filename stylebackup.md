/_ ================
Fonts
================ _/
@import url("https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500;700;900&display=swap");
/_ ================
Variables
================ _/
:root {
--Prim-1: hsl(225, 100%, 94%);
--prim-2: hsl(245, 75%, 52%);
--secon-light: hsl(225, 100%, 98%);
--secon-a2: hsl(224, 23%, 55%);
--secon-drk: hsl(223, 47%, 23%);
--prim-3: #766cf1;
--radius: 1rem;
--spacing: 0.25rem;
--transition: all 0.3s linear;
--ff-prim: "Red Hat Display", sans-serif;
}
/_ ================
Global styles
================ _/

- {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  }

img {
width: 100%;
display: block;
}
body {
background: url("./images/pattern-background-mobile.svg");
background-size: 100%;
background-repeat: no-repeat;
background-color: var(--Prim-1);
width: 100%;
height: 100vh;
display: grid;
place-items: center;
}
@media screen and (min-width: 768px) {
body {
background: url(/images/pattern-background-desktop.svg);
background-size: 100%;
background-repeat: no-repeat;
background-color: var(--Prim-1);
}
}
.container {
background: white;
height: 38rem;
width: 22rem;
border-radius: var(--radius);
display: flex;
flex-direction: column;
justify-content: space-between;
max-width: 100vw;
}
.hero img {
border-top-left-radius: var(--radius);
border-top-right-radius: var(--radius);
}
.title h1 {
font-family: var(--ff-prim);
margin: 0 auto;
text-align: center;
color: var(--secon-drk);
font-weight: 900;
max-width: 80%;
}
.title p {
font-family: var(--ff-prim);
margin-top: 1rem;
text-align: center;
color: var(--secon-a2);
font-weight: 500;
font-size: 1rem;
line-height: 1.5rem;
}

.plans {
display: grid;
grid-template-columns: 0.8fr 1.2fr 1fr;
justify-content: space-between;
background: var(--secon-light);
border-radius: 0.8rem;
column-gap: 1rem;
padding: 1rem;
margin-left: 1rem;
margin-right: 1rem;
}
.music-icon {
justify-self: center;
align-self: center;
}
.price {
align-self: center;
font-family: var(--ff-prim);
font-size: 1rem;
font-weight: 700;
color: var(--secon-drk);
font-size: 0.9rem;
}
.price span {
color: var(--secon-a2);
font-weight: 500;
max-width: 800;
}
.plans a {
align-self: center;
margin-left: 2rem;
color: var(--prim-2);
}
.plans a:hover {
color: var(--prim-3);
text-decoration: none;
}
.buttons {
align-self: center;
justify-self: center;
}
.main-btn {
background: var(--prim-2);
padding: 1rem 4.5rem;
width: 100%;
border-radius: 0.8rem;
border: none;
font-family: var(--ff-prim);
color: #fff;
cursor: pointer;
font-weight: 900;
font-size: 1rem;
box-shadow: 0px 20px 20px rgba(56, 42, 225, 0.190291);
transition: var(--transition);
margin-bottom: 0.8rem;
}
main button:hover {
background: var(--prim-3);
}
.cnl-btn {
background: transparent;
text-align: center;
padding: 1rem 0;
width: 100%;
border-radius: 0.8rem;
border: none;
font-family: var(--ff-prim);
color: #fff;
cursor: pointer;
font-weight: 900;
font-size: 1rem;
margin-bottom: 1rem;
transition: var(--transition);
}
#cbtn:hover {
color: var(--secon-drk);
}
.cnl-btn a {
text-decoration: none;
}
