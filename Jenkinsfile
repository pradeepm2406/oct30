def message = "Hello World"
//A small  Message to be defined as a param for the current jobs t
def lowerCaseMessage = message.toLowerCase()
def splitWords = message.split(" ")

node(){
    stage("Hello World in lower Case"){
        
        //Nachricht
        echo message
    }
    stage("Hello World in lower Case"){
  
        //Nachricht in LowerCase innerhalb eines String
        echo "$message converted to lower case is: $lowerCaseMessage"
        
        //Nun wird jedes einzelne Wort, welches durch ein Leerzeichen getrennt wird ausgegeben.
        splitWords.each{
            echo it
        }
    }
}
