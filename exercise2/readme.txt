Only edit the ready.js file. 
sample.json and answer.json are for reference. 

Rules

For this exercise, you need to write a script to fetch a json file (sample.json) via ajax and parse all of the values that are floats into integers. For example, 89.9679876 --> 9 and {id: 3.2323} --> {id: 3}.  

The end algorithm should not have any hardcoded values in it, it should work with any key names, IE there should be no difference in parsing {name: 15.5} and {aName: 15.5}.

To load the sample.json file, use a jquery ajax request to load the json. Once loaded, begin to recursively parse the json and convert all floats into integers. For submission, all you need to do is echo the output to the console. The output in the console should be identicall to answer.json.  



For example, this is pseudo code

// Load json
// sample.json = {"id": 47.075699,"subId": {"number": 89.169847,"name": "mollit"}}

$load('sample.json')
  .done(function(data) {
    for (var i in data) {
      data = data.round
    }
    console.log(data)
  })

// output = {"id": 47,"subId": {"number": 89,"name": "mollit"}}

Please zip up all of the files and send it to us; we will then run whatever you have in the browser and check it with the answer.json file.


Tips 

This a difficult question; try to get as much done as possible and document in the comments all of the steps taken. We recommend looking into writing recursive and functional javascript.