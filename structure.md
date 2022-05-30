# Car dealer

## Model: Used Car

## Table: Cars

- id:                       BIGINT               - PRYMARY_KEY(NOTNULL, AUTOINCREMENT, UNIQUE)
- brand:                    VARCHAR(50)          - NOTNULL
- description               TEXT                 - NULL
- image                     VARCHAR(255)         - NULL
- motor_power_supply:       VARCHAR(30)          - NOTNULL
- engine_displacement:      DECIMAL(6, 2)        - NULL
- power:                    DECIMAL(6, 2)        - NULL
- matriculation:            INT                  - NOTNULL  
- price:                    DECIMAL(10, 2)       - NULL
- trasmission:              VARCHAR(20)          - NULL
- mileage:                  INT                  - NOTNULL
- types of bodywork:        VARCHAR(30)          - NOTNULL
- number_of_doors:          INT                  - NULL
- number_of_seats:          INT                  - NULL
- exterior_color:           VARCHAR(30)          - NULL
- interior_color:           VARCHAR(30)          - NULL 
- interior_material:        VARCHAR(20)          - NULL
- last_maintenance:         DATE                 - NULL
- country_of_origin:        VARCHAR(20)          - NULL
- number_of_key:            INT                  - NULL    
- emission_class:           VARCHAR(10)          - NOTNULL
- imperfections:            VARCHAR(255)         - NULL
- numbers_of_oweners:       INT                  - NULL
- available:                TYNYINT              - NOTNULL DEFAULT(0)
