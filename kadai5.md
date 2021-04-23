```
@startuml
start
:weather=天気情報;
if(weather=0) then (快晴です)
  :快晴です;
 else if (weather=1)then (曇りです)
 :曇りです;
 else if (weather=2)then (雨です)
 :雨です;
 else then (不明です)
 :不明です;
 else
 end
 @enduml
