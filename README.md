# Структура проектов
Определим следующую структуру проекта:
- .../[%data-structure-name%] <- it's branch
    - docs/
        - Data-structure-definition.md (определение структуры данных)
        - How-it-works.md (принципы работы)
        - Interface.md (основные операции над структурой данных)
    - %Language%/
        - "CScience.DataStructures." + %DataStructureName%/ <- solution directory
            - src/ <- project directory
            - tests/ <- test project directory
