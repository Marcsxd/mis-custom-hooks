# useFetch hook

Ejemplo: 
```
    const url = 'endpoint de una api';
    const { state } = useFetch( url )
    const {data /*null*/, loading /*true*/, error /*null*/} = state; // <-- valores por defecto
    
```