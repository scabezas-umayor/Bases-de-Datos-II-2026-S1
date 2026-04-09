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
