# Advance-Calculator-in-bdfd
Advance Calculator Code for use in 'Bot Designer For Discord'. My discord contact jaggu_0#5899

````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````

Variables required
 
calc = 0
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 1 
 
Trigger:(your choice)
 
Type: BDSript
 
Code:
 
$nomention
$addField[Calculator;0]
$addButton[no;7;7;secondary;no;]
$addButton[no;8;8;secondary;no;]
$addButton[no;9;9;secondary;no;]
$addButton[no;x;x;primary;no;]
$addButton[yes;4;4;secondary;no;]
$addButton[no;5;5;secondary;no;]
$addButton[no;6;6;secondary;no;]
$addButton[no;+;+;primary;no;]
$addButton[no;-;-;primary;no;]
$addButton[yes;1;1;secondary;no;]
$addButton[no;2;2;secondary;no;]
$addButton[no;3;3;secondary;no;]
$addButton[no;=;=;primary;no;]
$addButton[no;<;<;danger;no;]
$addButton[yes;0;0;secondary;no;]
$addButton[no;00;00;secondary;no;]
$addButton[no;000;000;secondary;no;]
$addButton[no;ac;AC;danger;no;]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````

Command 2
 
Trigger: $onInteraction[1]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]1;-1];true;$getServerVar[calc] 1;-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]1;-1];true;$getServerVar[calc] 1;-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 3
 
Trigger: $onInteraction[2]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]2;-1];true;$getServerVar[calc] 2;-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]2;-1];true;$getServerVar[calc] 2;-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 4
 
Trigger: $onInteraction[3]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]3;-1];true;$getServerVar[calc] 3;-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]3;-1];true;$getServerVar[calc] 3;-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 5
 
Trigger: $onInteraction[4]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]4;-1];true;$getServerVar[calc] 4;-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]4;-1];true;$getServerVar[calc] 4;-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 6
 
Trigger: $onInteraction[5]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]5;-1];true;$getServerVar[calc] 5;-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]5;-1];true;$getServerVar[calc] 5;-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 7
 
Trigger: $onInteraction[6]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]6;-1];true;$getServerVar[calc] 6;-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]6;-1];true;$getServerVar[calc] 6;-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 8
 
Trigger: $onInteraction[7]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]7;-1];true;$getServerVar[calc] 7;-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]7;-1];true;$getServerVar[calc] 7;-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 9
 
Trigger: $onInteraction[8]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]8;-1];true;$getServerVar[calc] 8;-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]8;-1];true;$getServerVar[calc] 8;-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 10
 
Trigger: $onInteraction[9]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]9;-1];true;$getServerVar[calc] 9;-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]9;-1];true;$getServerVar[calc] 9;-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````

Command 11
 
Trigger: $onInteraction[0]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkCondition[$splitText[$getTextSplitLength]==0];true;$getServerVar[calc];-1];false;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]0;-1];true;$getServerVar[calc] 0;-1];-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkCondition[$splitText[$getTextSplitLength]==0];true;$getServerVar[calc];-1];false;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]0;-1];true;$getServerVar[calc] 0;-1];-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 12
 
Trigger: $onInteraction[00]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkCondition[$splitText[$getTextSplitLength]==0];true;$getServerVar[calc];-1];false;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]00;-1];true;$getServerVar[calc] 0;-1];-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkCondition[$splitText[$getTextSplitLength]==0];true;$getServerVar[calc];-1];false;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]00;-1];true;$getServerVar[calc] 0;-1];-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 13
 
Trigger: $onInteraction[000]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
 
$addField[Calculator;$replaceText[$replaceText[$checkCondition[$splitText[$getTextSplitLength]==0];true;$getServerVar[calc];-1];false;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]000;-1];true;$getServerVar[calc] 0;-1];-1]]
$setServerVar[calc;$replaceText[$replaceText[$checkCondition[$splitText[$getTextSplitLength]==0];true;$getServerVar[calc];-1];false;$replaceText[$replaceText[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·];false;$getServerVar[calc]000;-1];true;$getServerVar[calc] 0;-1];-1]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 14
 
Trigger: $onInteraction[/]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
$onlyIf[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·]==false;You already have an operator at the end that is $splitText[$getTextSplitLength]]
$addField[Calculator;$getServerVar[calc] Ã·]
$setServerVar[calc;$getServerVar[calc] Ã·]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 15
 
Trigger: $onInteraction[x]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
$onlyIf[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·]==false;You already have an operator at the end that is $splitText[$getTextSplitLength]]
$addField[Calculator;$getServerVar[calc] x]
$setServerVar[calc;$getServerVar[calc] x]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 16
 
Trigger: $onInteraction[+]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
$onlyIf[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·]==false;You already have an operator at the end that is $splitText[$getTextSplitLength]]
$addField[Calculator;$getServerVar[calc] +]
$setServerVar[calc;$getServerVar[calc] +]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 17
 
Trigger: $onInteraction[-]
 
Type: BDSript 2
 
Code:
 
$nomention
$textSplit[$getServerVar[calc]; ]
$onlyIf[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·]==false;You already have an operator at the end that is $splitText[$getTextSplitLength]]
$addField[Calculator;$getServerVar[calc] -]
$setServerVar[calc;$getServerVar[calc] -]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 18
 
Trigger: $onInteraction[=]
 
Type: BDSript 2
 
Code:
 
$nomention
$onlyIf[$checkContains[$getServerVar[calc];+;-;x;Ã·]==true;you havenâ€™t chosen any operator in your calculation yet please choose one]
$textSplit[$getServerVar[calc]; ]
$onlyIf[$checkContains[$splitText[$getTextSplitLength];+;-;x;Ã·]==false;Your calculation ends with an operator which kinda doesnâ€™t make any sense]
$addField[Calculator;$getServerVar[calc] = $calculate[$replaceText[$replaceText[$getServerVar[calc];x;*;-1];Ã·;/;-1]]]
$setServerVar[calc;$calculate[$replaceText[$replaceText[$getServerVar[calc];x;*;-1];Ã·;/;-1]]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 19
 
Trigger: $onInteraction[ac]
 
Type: BDSript 2
 
Code:
 
$nomention
$resetServerVar[calc]
$addField[Calculator;$getServerVar[calc]]
 
````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
 
Command 20
 
Trigger: $onInteraction[<]
 
Type: BDSript 2
 
Code:
 
$nomention
 
$textSplit[$getServerVar[calc];]
 
$removeSplitTextElement[$getTextSplitLength]
 
$addField[Calculator;$joinSplitText[]]
$setServerVar[calc;$joinSplitText[]]
 
CONGRATS, YOU'VE MADE IT TO THE END!

````````````````````````````````````````````````````````````
````````````````````````````````````````````````````````````
