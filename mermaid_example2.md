 ```
graph LR;
enter[入店];
consider[検討];
order[注文];
confirm{材料有無};
cook[調理];
serve[料理提供];
enter --> consider;
consider --> order;
order --> confirm;
confirm -- 無し --> consider;
confirm -- 有り --> cook;
cook --> serve;
```
    
 ```mermaid
graph LR;
enter[入店];
consider[検討];
order[注文];
confirm{材料有無};
cook[調理];
serve[料理提供];
enter --> consider;
consider --> order;
order --> confirm;
confirm -- 無し --> consider;
confirm -- 有り --> cook;
cook --> serve;
```