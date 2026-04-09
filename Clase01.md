Habilitar la salida estándar
```
SET SERVEROUTPUT ON;
```

Hola Mundo en PL/SQL de Oracle

```
BEGIN
    DBMS_OUTPUT.PUT_LINE('Hola Mundo');
END;
```

Variables y tipos de datos
```
DECLARE
    -- v_variable   TIPO DE DATO    := (ASIGNACION DE VALOR) TERMINA CON ;
    v_nota      NUMBER(3,2) := 3.94; -- 9.99
BEGIN
    DBMS_OUTPUT.PUT_LINE('NOTA: ' || v_nota);
END;
```

Variables y tipos de datos, trabajando con un contador
```
DECLARE
    v_contador  PLS_INTEGER := 0; -- numero entero de oracle
BEGIN
    -- editar el valor de una variable
    v_contador := 100;
    DBMS_OUTPUT.PUT_LINE('CONTADOR: ' || v_contador);
END;
```

Variables y tipos de datos, hacer un ++
```
DECLARE
    v_contador  PLS_INTEGER := 0; -- numero entero de oracle
BEGIN
    -- editar el valor de una variable
    v_contador := 100;
    -- un ++
    v_contador := v_contador + 1;
    DBMS_OUTPUT.PUT_LINE('CONTADOR: ' || v_contador);
END;
```



