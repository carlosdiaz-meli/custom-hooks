# useFetch Hook

Ejemplo de uso:
```JavaScript
    const url = 'endpoint de una api';
    const { data, loading, error } = useFetch(url);
    // data: [], {}, null
    // loading: true, false
    // error: null, 'No se pudo cargar la info'
```