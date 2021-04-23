```
@startuml
start
:weather=天気情報;
if(weather) then (0)
  :快晴です;
 elseif then (1)
 :曇りです;
 elseif then (2)
 :雨です;
 elseif then (その他)
 :不明です;
 else
 end
 @enduml
