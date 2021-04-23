```
@startuml
start
:weather=天気情報;
if(weather) then (0)
  :快晴です;
 else if then (1)
 :曇りです;
 else if then (2)
 :雨です;
 else if then (その他)
 :不明です;
 else
 end
 @enduml
