local storage> needs to be converted to a string before you store it. Then store it.>Then you retrieve it > convert it back to a data structure.

converting from a string to a data structure is a parse

turning data into a string is called stringify

["Kenneth", true, 34, "Danny-Man", true, 66, "Sugey", true, 92]

var studentsStringified = JSON.stringify(students)
undefined

studentsStringified
"["Kenneth",true,34,"Danny-Man",true,66,"Sugey",true,92]"

localStorage.setItem('demo', studentsStringified)
undefined

localStorage.setItem('demoWrongWay', students)
undefined

var studentsRetrieved = localStorage.getItem('demo')
undefined

studentsRetrieved
["Kenneth",true,34,"Danny-Man",true,66,"Sugey",true,92]"

JSON.parse(studentsRetrieved)

["Kenneth", true, 34, "Danny-Man", true, 66, "Sugey", true, 92]

var studentsParsed = JSON.parse(studentsRetrieved)
undefined

studentsParsed
["Kenneth", true, 34, "Danny-Man", true, 66, "Sugey", true, 92]

students
["Kenneth", true, 34, "Danny-Man", true, 66, "Sugey", true, 92]~~~


+ if local storage exists, retrieve parse local storage. Assign that to images aray. 
}else create our image objects ...then carry on.


+ JSON stands for javaSript object notation. way of sharing information on the internet.
