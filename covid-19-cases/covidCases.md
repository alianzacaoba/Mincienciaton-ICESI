## Get a list of Covid-19 cases in Valle del Cauca - Colombia

Through the following HTTP request, you can obtain a list of COVID-19 cases that have taken place in the department of Valle del Cauca - Colombia.

The source of the information is Datos Abiertos Colombia.
``link:`` https://estrategia.gobiernoenlinea.gov.co/623/w3-article-9407.html

### Request overview
``Basics``
* ``Request method:`` GET
* ``Endpoint:`` https://www.datos.gov.co/resource/gt2j-8ykr.json
* ``Query param`` ?$where=codigo_departamento =76
* ``Full endpoint:`` https://www.datos.gov.co/resource/gt2j-8ykr.json$where=codigo_departamento =76

``Headers``
* app_token: 6b4mz7ujeaf515mfyqqnv5byzo6hfsp5ar3i9hmfdtqc6s9ebn

``Response body``

```
[
    {
        "id_de_caso": "2",
        "fecha_de_notificaci_n": "2020-03-06T00:00:00.000",
        "c_digo_divipola": "76111",
        "ciudad_de_ubicaci_n": "Guadalajara de Buga",
        "departamento": "Valle del Cauca",
        "atenci_n": "Recuperado",
        "edad": "34",
        "sexo": "M",
        "tipo": "Importado",
        "estado": "Leve",
        "pa_s_de_procedencia": "ESPAÑA",
        "fis": "2020-03-04T00:00:00.000",
        "fecha_diagnostico": "2020-03-09T00:00:00.000",
        "fecha_recuperado": "2020-03-19T00:00:00.000",
        "fecha_reporte_web": "2020-03-09T00:00:00.000",
        "tipo_recuperaci_n": "PCR",
        "codigo_departamento": "76",
        "codigo_pais": "724",
        "pertenencia_etnica": "Otro"
    },
    {
        "id_de_caso": "14",
        "fecha_de_notificaci_n": "2020-03-10T00:00:00.000",
        "c_digo_divipola": "76520",
        "ciudad_de_ubicaci_n": "Palmira",
        "departamento": "Valle del Cauca",
        "atenci_n": "Recuperado",
        "edad": "48",
        "sexo": "M",
        "tipo": "Importado",
        "estado": "Leve",
        "pa_s_de_procedencia": "ESPAÑA",
        "fis": "2020-03-07T00:00:00.000",
        "fecha_diagnostico": "2020-03-13T00:00:00.000",
        "fecha_recuperado": "2020-03-21T00:00:00.000",
        "fecha_reporte_web": "2020-03-13T00:00:00.000",
        "tipo_recuperaci_n": "PCR",
        "codigo_departamento": "76",
        "codigo_pais": "724",
        "pertenencia_etnica": "Otro"
    }
]
```

### cURL request
```
curl --location --request GET 'https://www.datos.gov.co/resource/gt2j-8ykr.json?$where=codigo_departamento%20=76' \
--header 'app_token: 6b4mz7ujeaf515mfyqqnv5byzo6hfsp5ar3i9hmfdtqc6s9ebn'
```
