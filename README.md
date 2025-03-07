# Task
Task Apps

## Solid Focus

```turtle
@prefix schema: <https://schema.org/> .
@prefix ical: <http://www.w3.org/2002/12/cal/ical#> .
@prefix crdt: <https://vocab.noeldemartin.com/crdt/> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

<#it>
    a schema:Action, ical:Vtodo;
    schema:name "Learn Solid";
    ical:summary  "Learn Solid";
    ical:priority 1;
    schema:description "This was created a long time ago";
    schema:actionStatus schema:CompletedActionStatus;
    ical:due "2019-01-01T00:00:00.000Z"^^xsd:dateTime;
    ical:completed "2018-12-25T00:00:00.000Z"^^xsd:dateTime.
```

https://github.com/NoelDeMartin/solid-focus/tree/aerogel/cypress/fixtures

## Solid OS

```turtle
:Iss1595415193957
    a ind:ClientCore, ind:Works;
    dc:title "Preferences";
    dct:created "2020-07-22T10:53:13Z"^^xsd:dateTime;
    wf:attachment so:solid-ui;
    wf:description
        "Preferences handling where personal prefs for the class of object in general are merged with those for the specific object from the user, and from the maker of the object.";
    wf:tracker ind:this.
```

https://solidos.solidcommunity.net/public/Roadmap/Tasks/state.ttl

## Simple JSON

```json
{
  "@id": "#1741275780.695",
  "@type": "Task",
  "title": "czech lesson",
  "completed": true,
  "created": "2025-03-06T15:43:00.695Z"
}
```

https://nosdav.net/f0af306a4f3e60f17d88210cbce6f1e7df6abaa79b501624f8be6c6a5d0981ac/todos.json
