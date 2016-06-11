# Структура проектов

[![Join the chat at https://gitter.im/CS-Challenge/data-structures](https://badges.gitter.im/CS-Challenge/data-structures.svg)](https://gitter.im/CS-Challenge/data-structures?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
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
