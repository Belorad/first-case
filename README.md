# Первый кейс по изучению командной строки Git  
В данном кейсе справочный материал по работе с командной строкой Git.  
А именно:
1. Файл gitcommands.
2. Файл savecommands.  

```mermaid
%% схема изменения статусов файлов в Git
graph LR;
  untracked      -- "git add"    --> staged+tracked;
  staged+tracked -- "git commit" --> tracked;
  tracked        -- "изменения"  --> modified;
  modified       -- "git add"    --> staged+tracked;
  staged+tracked -- "изменения"  --> modified;
``` 
---
Вообще мой основной репозиторий на [GitLab](https://gitlab.com/Belorad "Ivan Pertsev").  
Как бы на этом пока всё.