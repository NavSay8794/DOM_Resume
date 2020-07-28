var divC = document.createElement('div')
divC.setAttribute('class', 'container')
document.body.appendChild(divC)

var divHp = document.createElement('div')
divHp.setAttribute('class', 'headingPart')
document.querySelector('.container').appendChild(divHp)

var divfb = document.createElement('div')
divfb.setAttribute('class', 'fullback')
document.querySelector('.headingPart').appendChild(divfb)

var divwp = document.createElement('div')
divwp.setAttribute('class', 'whitepatch')
document.querySelector('.fullback').appendChild(divwp)

var mimg = document.createElement('img')
mimg.setAttribute('src', 'myimage1.jpg')
mimg.setAttribute('alt', 'My Profile')
mimg.setAttribute('class', 'imageDetails')
document.querySelector('.fullback').appendChild(mimg)

var divnb = document.createElement('div')
divnb.setAttribute('class', 'nameBlock')
document.querySelector('.fullback').appendChild(divnb)
var divn = document.createElement('div')
divn.setAttribute('class', 'namer')
document.querySelector('.nameBlock').appendChild(divn)

var n = document.querySelector('.namer')
n.innerHTML = 'Naveed Nisar Sayyed'

//address
var divAdd = document.createElement('div')
divAdd.setAttribute('class', 'addressBar')
document.querySelector('.container').appendChild(divAdd)
var divpara = document.createElement('div')
divpara.setAttribute('class', 'para')
document.querySelector('.addressBar').appendChild(divpara)

var address = document.querySelector('.para')
address.innerHTML =  "Senior Associate Consultant, Infosys | Mobile No: 7977413255 | Email:sayyednaveed107@gmail.com"

var hr = document.createElement('hr')
document.querySelector('.container').appendChild(hr)


//resumeBody
var divRb = document.createElement('div')
divRb.setAttribute('class', 'resumeBody')
document.querySelector('.container').appendChild(divRb)

var divLs = document.createElement('div')
divLs.setAttribute('class', 'leftSide')
document.querySelector('.resumeBody').appendChild(divLs)

var divSl = document.createElement('div')
divSl.setAttribute('class', 'spaceleft')
document.querySelector('.leftSide').appendChild(divSl)

var divpro = document.createElement('div')
divpro.setAttribute('class', 'profile')
document.querySelector('.spaceleft').appendChild(divpro)

var divjust1 = document.createElement('div')
divjust1.setAttribute('class', 'jdiv')
document.querySelector('.profile').appendChild(divjust1)

var proimg = document.createElement('img')
proimg.setAttribute('src', 'profile.png')
proimg.setAttribute('class', 'smallsizing')
document.querySelector('.jdiv').appendChild(proimg)

var span1 = document.createElement('span')
span1.setAttribute('class', 'heading')
span1.setAttribute('id', 'heading0')
document.querySelector('.jdiv').appendChild(span1)
var cO0 = document.querySelector('#heading0')
cO0.innerHTML = 'Career Objective'


var divcO = document.createElement('p')
divcO.setAttribute('class', 'carrobj')
document.querySelector('.profile').appendChild(divcO)
var cObj = document.querySelector('.carrobj')
cObj.innerHTML = 'Seeking a suitable position to use my knowledge and skills for the growth and enhancement of the organization while being resourceful and flexible'

var br1 = document.createElement('br')
document.querySelector('.spaceleft').appendChild(br1)

//academic
var divacad = document.createElement('div')
divacad.setAttribute('class', 'academic')
document.querySelector('.spaceleft').appendChild(divacad)

var divjust2 = document.createElement('div')
divjust2.setAttribute('class', 'jdiv1')
document.querySelector('.academic').appendChild(divjust2)

var acadimg = document.createElement('img')
acadimg.setAttribute('src', 'academic.png')
acadimg.setAttribute('class', 'smallsizing')
document.querySelector('.jdiv1').appendChild(acadimg)

var span2 = document.createElement('span')
span2.setAttribute('class', 'heading')
span2.setAttribute('id', 'heading1')
document.querySelector('.jdiv1').appendChild(span2)
var cO1 = document.querySelector('#heading1')
cO1.innerHTML = 'Academic Qualifications'

var br2 = document.createElement('br')
document.querySelector('.academic').appendChild(br2)

var divtable = document.createElement('div')
divtable.setAttribute('id', 'table')
document.querySelector('.academic').appendChild(divtable)

var tableSec= document.createElement('table')
tableSec.setAttribute('border','1')
tableSec.setAttribute('cellpadding','2')
tableSec.setAttribute('class', 'table')
document.querySelector('#table').appendChild(tableSec)

//first row
var tr1 = document.createElement('tr')
tr1.setAttribute('id', 'tr1')
document.querySelector('.table').appendChild(tr1)

var tr1td1 = document.createElement('td')
tr1td1.setAttribute('id' , 'tableC11')
document.querySelector('#tr1').appendChild(tr1td1)
var c1 = document.querySelector('#tableC11')
c1.innerText = 'Examination'

var tr1td2 = document.createElement('td')
tr1td2.setAttribute('id' , 'tableC12')
document.querySelector('#tr1').appendChild(tr1td2)
var c2 = document.querySelector('#tableC12')
c2.innerText = 'University'

var tr1td3 = document.createElement('td')
tr1td3.setAttribute('id' , 'tableC13')
document.querySelector('#tr1').appendChild(tr1td3)
var c3 = document.querySelector('#tableC13')
c3.innerText = 'College'    


var tr1td4 = document.createElement('td')
tr1td4.setAttribute('id' , 'tableC14')
document.querySelector('#tr1').appendChild(tr1td4)
var c4 = document.querySelector('#tableC14')
c4.innerText = 'Year'

var tr1td5 = document.createElement('td')
tr1td5.setAttribute('id' , 'tableC15')
document.querySelector('#tr1').appendChild(tr1td5)
var c5 = document.querySelector('#tableC15')
c5.innerText = 'CGPI'


//second row
var tr2 = document.createElement('tr')
tr2.setAttribute('id', 'tr2')
document.querySelector('.table').appendChild(tr2)

var tr2td1 = document.createElement('td')
tr2td1.setAttribute('id' , 'tableC21')
document.querySelector('#tr2').appendChild(tr2td1)
var c21 = document.querySelector('#tableC21')
c21.innerText = 'BE(Extc)'

var tr2td2 = document.createElement('td')
tr2td2.setAttribute('id' , 'tableC22')
document.querySelector('#tr2').appendChild(tr2td2)
var c22 = document.querySelector('#tableC22')
c22.innerText = 'Mumbai'

var tr2td3 = document.createElement('td')
tr2td3.setAttribute('id' , 'tableC23')
document.querySelector('#tr2').appendChild(tr2td3)
var c23 = document.querySelector('#tableC23')
c23.innerText = 'KJSCE'    


var tr2td4 = document.createElement('td')
tr2td4.setAttribute('id' , 'tableC24')
document.querySelector('#tr2').appendChild(tr2td4)
var c24 = document.querySelector('#tableC24')
c24.innerText = '2016'

var tr2td5 = document.createElement('td')
tr2td5.setAttribute('id' , 'tableC25')
document.querySelector('#tr2').appendChild(tr2td5)
var c25 = document.querySelector('#tableC25')
c25.innerText = '7.83'


//3rd row
var tr3 = document.createElement('tr')
tr3.setAttribute('id', 'tr3')
document.querySelector('.table').appendChild(tr3)


var tr3td1 = document.createElement('td')
tr3td1.setAttribute('id' , 'tableC31')
document.querySelector('#tr3').appendChild(tr3td1)
var c31 = document.querySelector('#tableC31')
c31.innerText = 'HSC'

var tr3td2 = document.createElement('td')
tr3td2.setAttribute('id' , 'tableC32')
document.querySelector('#tr3').appendChild(tr3td2)
var c32 = document.querySelector('#tableC32')
c32.innerText = 'Maharashtra'

var tr3td3 = document.createElement('td')
tr3td3.setAttribute('id' , 'tableC33')
document.querySelector('#tr3').appendChild(tr3td3)
var c33 = document.querySelector('#tableC33')
c33.innerText = 'G.N.Khalsa College'  


var tr3td4 = document.createElement('td')
tr3td4.setAttribute('id' , 'tableC34')
document.querySelector('#tr3').appendChild(tr3td4)
var c34 = document.querySelector('#tableC34')
c34.innerText = '2012'

var tr3td5 = document.createElement('td')
tr3td5.setAttribute('id' , 'tableC35')
document.querySelector('#tr3').appendChild(tr3td5)
var c35 = document.querySelector('#tableC35')
c35.innerText = '86.5%'

//fourth row

var tr4 = document.createElement('tr')
tr4.setAttribute('id', 'tr4')
document.querySelector('.table').appendChild(tr4)

var tr4td1 = document.createElement('td')
tr4td1.setAttribute('id' , 'tableC41')
document.querySelector('#tr4').appendChild(tr4td1)
var c41 = document.querySelector('#tableC41')
c41.innerText = 'SSC'

var tr4td2 = document.createElement('td')
tr4td2.setAttribute('id' , 'tableC42')
document.querySelector('#tr4').appendChild(tr4td2)
var c42 = document.querySelector('#tableC42')
c42.innerText = 'Maharashtra'

var tr4td3 = document.createElement('td')
tr4td3.setAttribute('id' , 'tableC43')
document.querySelector('#tr4').appendChild(tr4td3)
var c43 = document.querySelector('#tableC43')
c43.innerText = 'St. Pauls High School'

var tr4td4 = document.createElement('td')
tr4td4.setAttribute('id' , 'tableC44')
document.querySelector('#tr4').appendChild(tr4td4)
var c44 = document.querySelector('#tableC44')
c44.innerText = '2010'

var tr4td5 = document.createElement('td')
tr4td5.setAttribute('id' , 'tableC45')
document.querySelector('#tr4').appendChild(tr4td5)
var c45 = document.querySelector('#tableC45')
c45.innerText = '88.55%'


var br3 = document.createElement('br')
document.querySelector('.spaceleft').appendChild(br3)

//skills

var divskill = document.createElement('div')
divskill.setAttribute('class', 'skills')
document.querySelector('.spaceleft').appendChild(divskill)

var divjust3 = document.createElement('div')
divjust3.setAttribute('class', 'jdiv3')
document.querySelector('.skills').appendChild(divjust3)

var skillimg = document.createElement('img')
skillimg.setAttribute('src', 'skills.jpg')
skillimg.setAttribute('class', 'smallsizing')
document.querySelector('.jdiv3').appendChild(skillimg)

var span3 = document.createElement('span')
span3.setAttribute('class', 'heading')
span3.setAttribute('id', 'heading2')
document.querySelector('.jdiv3').appendChild(span3)
var cO2 = document.querySelector('#heading2')
cO2.innerHTML = 'Technical Skills'

var br3 = document.createElement('br')
document.querySelector('.skills').appendChild(br3)

//skills table

var tableSecSkil= document.createElement('table')
tableSecSkil.setAttribute('border','1')
tableSecSkil.setAttribute('class', 'tech')
document.querySelector('.skills').appendChild(tableSecSkil)

// //first row
var trs1 = document.createElement('tr')
trs1.setAttribute('id', 'trs1')
document.querySelector('.tech').appendChild(trs1)

var trs1td1 = document.createElement('td')
trs1td1.setAttribute('id' , 'tableCS11')
trs1td1.setAttribute('colspan' , '1')
trs1td1.setAttribute('class' , 'widthchange')
document.querySelector('#trs1').appendChild(trs1td1)
var c1 = document.querySelector('#tableCS11')
c1.innerText = 'HTML'

var trs1td2 = document.createElement('td')
trs1td2.setAttribute('id' , 'tableCS12')
trs1td2.setAttribute('colspan' , '1')
document.querySelector('#trs1').appendChild(trs1td2)
var inp1 = document.createElement('input')
inp1.setAttribute('type' , 'range')
inp1.setAttribute('min' , '1')
inp1.setAttribute('max' , '100')
inp1.setAttribute('value' , '10')
inp1.setAttribute('class' , 'slider')
document.querySelector('#tableCS12').appendChild(inp1)

//second row

var trs2 = document.createElement('tr')
trs2.setAttribute('id', 'trs2')
document.querySelector('.tech').appendChild(trs2)

var trs2td1 = document.createElement('td')
trs2td1.setAttribute('id' , 'tableCS21')
trs2td1.setAttribute('colspan' , '1')
trs2td1.setAttribute('class' , 'widthchange')
document.querySelector('#trs2').appendChild(trs2td1)
var c2 = document.querySelector('#tableCS21')
c2.innerText = 'CSS'

var trs2td2 = document.createElement('td')
trs2td2.setAttribute('id' , 'tableCS22')
trs2td2.setAttribute('colspan' , '1')
document.querySelector('#trs2').appendChild(trs2td2)
var inp2 = document.createElement('input')
inp2.setAttribute('type' , 'range')
inp2.setAttribute('min' , '1')
inp2.setAttribute('max' , '100')
inp2.setAttribute('value' , '10')
inp2.setAttribute('class' , 'slider')
document.querySelector('#tableCS22').appendChild(inp2)

//third row

var trs3 = document.createElement('tr')
trs3.setAttribute('id', 'trs3')
document.querySelector('.tech').appendChild(trs3)

var trs3td1 = document.createElement('td')
trs3td1.setAttribute('id' , 'tableCS31')
trs3td1.setAttribute('colspan' , '1')
trs3td1.setAttribute('class' , 'widthchange')
document.querySelector('#trs3').appendChild(trs3td1)
var c3 = document.querySelector('#tableCS31')
c3.innerText = 'BootStrap'

var trs3td2 = document.createElement('td')
trs3td2.setAttribute('id' , 'tableCS32')
trs3td2.setAttribute('colspan' , '1')
document.querySelector('#trs3').appendChild(trs3td2)
var inp3 = document.createElement('input')
inp3.setAttribute('type' , 'range')
inp3.setAttribute('min' , '1')
inp3.setAttribute('max' , '100')
inp3.setAttribute('value' , '10')
inp3.setAttribute('class' , 'slider')
document.querySelector('#tableCS32').appendChild(inp3)


//fourth row

var trs4 = document.createElement('tr')
trs4.setAttribute('id', 'trs4')
document.querySelector('.tech').appendChild(trs4)

var trs4td1 = document.createElement('td')
trs4td1.setAttribute('id' , 'tableCS41')
trs4td1.setAttribute('colspan' , '1')
trs4td1.setAttribute('class' , 'widthchange')
document.querySelector('#trs4').appendChild(trs4td1)
var c4 = document.querySelector('#tableCS41')
c4.innerText = 'JavaScript'

var trs4td2 = document.createElement('td')
trs4td2.setAttribute('id' , 'tableCS42')
trs4td2.setAttribute('colspan' , '1')
document.querySelector('#trs4').appendChild(trs4td2)
var inp4 = document.createElement('input')
inp4.setAttribute('type' , 'range')
inp4.setAttribute('min' , '1')
inp4.setAttribute('max' , '100')
inp4.setAttribute('value' , '10')
inp4.setAttribute('class' , 'slider')
document.querySelector('#tableCS42').appendChild(inp4)

var br4 = document.createElement('br')
document.querySelector('.spaceleft').appendChild(br4)


//work ek

var divwex = document.createElement('div')
divwex.setAttribute('class', 'workExp')
document.querySelector('.spaceleft').appendChild(divwex)

var divjust4 = document.createElement('div')
divjust4.setAttribute('class', 'jdiv4')
document.querySelector('.workExp').appendChild(divjust4)

var workeximg = document.createElement('img')
workeximg.setAttribute('src', 'workExp.png')
workeximg.setAttribute('class', 'smallsizing')
document.querySelector('.jdiv4').appendChild(workeximg)

var span4 = document.createElement('span')
span4.setAttribute('class', 'heading')
span4.setAttribute('id', 'heading3')
document.querySelector('.jdiv4').appendChild(span4)
var cO3 = document.querySelector('#heading3')
cO3.innerHTML = 'Work Experience'

var br3 = document.createElement('br')
document.querySelector('.workExp').appendChild(br3)

var divjust5 = document.createElement('div')
divjust5.setAttribute('class', 'jdiv5')
document.querySelector('.workExp').appendChild(divjust5)

var ul1 = document.createElement('ul')
ul1.setAttribute('class', 'list')
document.querySelector('.jdiv5').appendChild(ul1)

var li1 = document.createElement('li')
li1.setAttribute('id', 'l1')
document.querySelector('.list').appendChild(li1)
var l1 = document.getElementById('l1')
l1.innerHTML = 'Having a total work experience of 4 years while currently working in Infosys as <strong> UI professional </strong> for the past 6 months and having a 3 years 6 months of working experience in Accenture.'

var br5 = document.createElement('br')
document.querySelector('.list').appendChild(br5)

var li2 = document.createElement('li')
li2.setAttribute('id', 'l2')
document.querySelector('.list').appendChild(li2)
var l2 = document.getElementById('l2')
l2.innerHTML = 'Trained in FrontEnd technologies like HTML, CSS and JavaScript and Backend Technologies Like NodeJs.'

var br6 = document.createElement('br')
document.querySelector('.list').appendChild(br6)

var li3 = document.createElement('li')
li3.setAttribute('id', 'l3')
document.querySelector('.list').appendChild(li3)
var l3 = document.getElementById('l3')
l3.innerHTML = 'Worked on automation using Blue-Prism in RPA (Robotics Process Automation) and have an experience of 1.5 years.'

var br5 = document.createElement('br')
document.querySelector('.list').appendChild(br5)

var li4 = document.createElement('li')
li4.setAttribute('id', 'l4')
document.querySelector('.list').appendChild(li4)
var l4 = document.getElementById('l4')
l4.innerHTML = 'Daily Monitoring of Software Robots in BluePrism.'

//right side
var divRs = document.createElement('div')
divRs.setAttribute('class', 'rightSide')
document.querySelector('.resumeBody').appendChild(divRs)

var divSr = document.createElement('div')
divSr.setAttribute('class', 'spaceright')
document.querySelector('.rightSide').appendChild(divSr)

var divwexr = document.createElement('div')
divwexr.setAttribute('class', 'workExp')
divwexr.setAttribute('id', 'workExp')
document.querySelector('.spaceright').appendChild(divwexr)

var divjust6 = document.createElement('div')
divjust6.setAttribute('class', 'jdiv6')
document.querySelector('#workExp').appendChild(divjust6)

var workeximg1 = document.createElement('img')
workeximg1.setAttribute('src', 'workExp.png')
workeximg1.setAttribute('class', 'smallsizing')
document.querySelector('.jdiv6').appendChild(workeximg1)

var span5 = document.createElement('span')
span5.setAttribute('class', 'heading')
span5.setAttribute('id', 'heading4')
document.querySelector('.jdiv6').appendChild(span5)
var cO4 = document.querySelector('#heading4')
cO4.innerHTML = 'Work Experience'

var br6 = document.createElement('br')
document.querySelector('.workExp').appendChild(br6)

var divjust7 = document.createElement('div')
divjust7.setAttribute('class', 'jdiv7')
document.querySelector('#workExp').appendChild(divjust7)

var ul2 = document.createElement('ul')
ul2.setAttribute('class', 'list')
ul2.setAttribute('id', 'list')
document.querySelector('.jdiv7').appendChild(ul2)

var li5 = document.createElement('li')
li5.setAttribute('id', 'l5')
document.querySelector('#list').appendChild(li5)
var l5 = document.getElementById('l5')
l5.innerHTML = 'Currently working towards solving the UI related issues of the client website.Incidents related to CSS and JavaScript are raised and we are to resolve the issues using CSS and JS'

var br7 = document.createElement('br')
document.querySelector('#list').appendChild(br7)

var li6 = document.createElement('li')
li6.setAttribute('id', 'l6')
document.querySelector('#list').appendChild(li6)
var l6 = document.getElementById('l6')
l6.innerHTML = 'Handling issues related to the Errors related to the working of the Software Robots in BluePrism.'



//Project

var divPr = document.createElement('div')
divPr.setAttribute('class', 'project')
document.querySelector('.spaceright').appendChild(divPr)

var divjust8 = document.createElement('div')
divjust8.setAttribute('class', 'jdiv8')
document.querySelector('.project').appendChild(divjust8)

var prjimg = document.createElement('img')
prjimg.setAttribute('src', 'project.jpg')
prjimg.setAttribute('class', 'smallsizing')
document.querySelector('.jdiv8').appendChild(prjimg)

var span6 = document.createElement('span')
span6.setAttribute('class', 'heading')
span6.setAttribute('id', 'heading5')
document.querySelector('.jdiv8').appendChild(span6)
var cO5 = document.querySelector('#heading5')
cO5.innerHTML = 'Projects'

// var br6 = document.createElement('br')
// document.querySelector('.project').appendChild(br6)

var divjust9 = document.createElement('div')
divjust9.setAttribute('class', 'jdiv9')
document.querySelector('.project').appendChild(divjust9)

var projectP1 = document.createElement('p')
projectP1.setAttribute('class' , 'heading')
projectP1.setAttribute('id' , 'projectP1')
projectP1.setAttribute('style' , 'font-size:1.5rem;')
document.querySelector('.jdiv9').appendChild(projectP1)
var pp1 = document.getElementById('projectP1')
pp1.innerHTML = 'PROJECT: APPLE'

var ul3 = document.createElement('ul')
ul3.setAttribute('class', 'list')
ul3.setAttribute('id', 'list1')
document.querySelector('.jdiv9').appendChild(ul3)

var li7 = document.createElement('li')
li7.setAttribute('id', 'l7')
document.querySelector('#list1').appendChild(li7)
var l7 = document.getElementById('l7')
l7.innerHTML = 'The work aims to serve the client by solving the CSS and JavaScript issues that occur on the Front end of the official client website'

var br8 = document.createElement('br')
document.querySelector('#list1').appendChild(br8)

var li8 = document.createElement('li')
li8.setAttribute('id', 'l8')
document.querySelector('#list1').appendChild(li8)
var l8 = document.getElementById('l8')
l8.innerHTML = 'Handling issues related to the Errors related to the working of the Software Robots in BluePrism.'


var divjust10 = document.createElement('div')
divjust10.setAttribute('class', 'jdiv10')
document.querySelector('.project').appendChild(divjust10)

var projectP2 = document.createElement('p')
projectP2.setAttribute('class' , 'heading')
projectP2.setAttribute('id' , 'projectP2')
projectP2.setAttribute('style' , 'font-size:1.5rem;')
document.querySelector('.jdiv10').appendChild(projectP2)
var pp2 = document.getElementById('projectP2')
pp2.innerHTML = 'PROJECT: SOCGEN'

var ul4 = document.createElement('ul')
ul4.setAttribute('class', 'list')
ul4.setAttribute('id', 'list2')
document.querySelector('.jdiv10').appendChild(ul4)

var li9 = document.createElement('li')
li9.setAttribute('id', 'l9')
document.querySelector('#list2').appendChild(li9)
var l9 = document.getElementById('l9')
l9.innerHTML = 'The project aims to serve the client by maintaining the financial data of the client that is generated on a daily basis. Daily Processing of Broker data is done as per the requirements from the User.'

var br9 = document.createElement('br')
document.querySelector('#list2').appendChild(br9)

var li10 = document.createElement('li')
li10.setAttribute('id', 'l10')
document.querySelector('#list2').appendChild(li10)
var l10 = document.getElementById('l10')
l10.innerHTML = 'The Broker data is compared with the user provided data. The entire process is done using software robots programmed in Blue Prism.'

var br10 = document.createElement('br')
document.querySelector('#list2').appendChild(br10)

var li11 = document.createElement('li')
li11.setAttribute('id', 'l11')
document.querySelector('#list2').appendChild(li11)
var l11 = document.getElementById('l11')
l11.innerHTML = 'Working on the errors that occur while running the bots, debugging the errors and maintaining the bots in proper conditions is the role.Solving User tickets and incidents whenever raised by the user'
