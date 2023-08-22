// 大部分用groovy語法

node(''){  
    stage('basic') { 
        // numeric
        varableOne  = 1
        varableTwo  = 2
        print( varableOne + varableTwo)
        
        // string
        stringSample  = "Hello world"
        print( stringSample )
        print( stringSample[0..3] ) // //Prints a string starting from Index 1 to 3
        print( stringSample + "-append-string")
        
        // boolean
        booleanTrue  = true
        booleanFalse = false
        print(booleanTrue)
        print(booleanFalse)
        
        // list
        listExample = ['a', 'b', 'c']
        print( listExample )
        print( listExample[0] ) // get list
        
    }
    stage('If/Else Statement'){
      a = 2
      if(a<100) { 
         print("The value is less than 100")
      } else    { 
         print("The value is greater than 100")
      } 
    }
    
    stage('loop'){
        // prints 'a', 'b' and 'c'
        for (i in [ 'a', 'b', 'c' ]) {
            echo i
        }
        
        for (i in [ 'a', 'b', 'c' ]) {
            echo i
        }        
    }    
    
    stage('use parameter'){
        parameterExample = "${env.PARAMETER_EXAMPLE}"
        print(parameterExample)
    }
    
    stage('use shell script'){
        varableSting = 'hello'
        print(varableSting)
        sh '''
            whoami
            pwd
            ls -al
            ip addr
            
            # use Variable
            echo $varableSting
        '''
    }
}