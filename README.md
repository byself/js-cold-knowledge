# js冷知识

`
    ([][[]]+[])      [+!![]]  +  ([]+{})  [!+[]+!![]]
    
    ([][0]+[])       [+true]  +  (""+{})  [!0+true]
    
    (undefined+[])   [1]      +  ("[object Object]")  [1+true]
    
    "undefined"[1] + "[object Object]"[2]
    
    "n" + "b"
    
    "nb"
    =============================================
    
    +[]  =   0
    -[]  =  -0
    
    +[[]] = 0
    -[[]] = 0
    
    +[[[]]] = 0
    -[[[]]] = 0
    
    ![]  =  false
    !![] =  true
    
    [] + [] = ""
    [] - [] = 0
    
    [][0] = undefined
    
    undefined + [] = "undefined"
    
    null + [] = "null"
    
    "" + {} = "[object Object]"
    [] + {} = "[object Object]"
    
    +true =  1
    -true = -1
    
    +false = 0
    -false = -0
    
    [] + true = "true"
    
    !{} = false
    !!{} = true
`