
{!../../../docs/missing-translation.md!}


<p align="center">
  <a href="https://fastapi.tiangolo.com"><img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" alt="FastAPI"></a>
</p>
<p align="center">
    <em>FastAPI Framework, Super schnell, leicht zu lernen, schnell zu schreiben, bereit für den produktiven Einsatz</em>
</p>
<p align="center">
<a href="https://github.com/tiangolo/fastapi/actions?query=workflow%3ATest" target="_blank">
    <img src="https://github.com/tiangolo/fastapi/workflows/Test/badge.svg" alt="Test">
</a>
<a href="https://codecov.io/gh/tiangolo/fastapi" target="_blank">
    <img src="https://img.shields.io/codecov/c/github/tiangolo/fastapi?color=%2334D058" alt="Coverage">
</a>
<a href="https://pypi.org/project/fastapi" target="_blank">
    <img src="https://img.shields.io/pypi/v/fastapi?color=%2334D058&label=pypi%20package" alt="Package version">
</a>
</p>

---

**Documentation**: <a href="https://fastapi.tiangolo.com" target="_blank">https://fastapi.tiangolo.com</a>

**Quellcode**: <a href="https://github.com/tiangolo/fastapi" target="_blank">https://github.com/tiangolo/fastapi</a>

---

FastAPI ist ein modernes, schnelles (performantes), Web-Framework zum programmieren von APIs mit Python 3.6+ basierend auf der standard Python-Autovervollständigung.

Die Haupt-Features sind:

* **Schnell**: Sehr schnell, so schnell wie **NodeJS** oder **Go** (Dank Starlette und Pydantic). [Eines der schnellsten Python-Frameworks, die existieren](#performance).

* **Schnell zum Programmieren**: Steigert die Geschwindigkeit Features zu programmiern um 200% bis 300%. *
* **Weniger Bugs**: Reduziert ungefähr 40% der Bugs, die durch den Menschen (Entwicklers) entstehen. *
* **Intiutiv**: Hervorragender Editor-Support. <abbr title="also known as auto-complete, autocompletion, IntelliSense">Autovervollständigung</abbr> überall. Verliere weniger Zeit beim Debuggen.
* **Einfach**: Designed einfach zu benutzen und zu lernen. Verschwende weniger Zeit, die Dokumentation zu lesen.
* **Kurz**: Minimiere Code-Duplikationen. Mehrere Merkmale aus jeder Parameterdeklaration. Weniger Bugs.
<!-- Multiple features from each parameter declaration = I don't know how 2 translate it better, so it is a TODO -->
* **Robust**: Bekomme produktionsreifen Code mit automatischer, interaktiver Dokumentation.
* **Basiert auf Standards**: Basiert auf (und is völlig kompatible mit) den Offenen Standards für APIs: <a href="https://github.com/OAI/OpenAPI-Specification" class="external-link" target="_blank">OpenAPI</a> (früher bekannt als Swagger) und dem <a href="https://json-schema.org/" class="external-link" target="_blank">JSON Schema</a>.

<small>* basierend auf Tests eines internen Entwickler-Teams, welches produktionsreife Applicationen programmiert.</small>

## Sponsoren

<!-- sponsors -->

{% if sponsors %}
{% for sponsor in sponsors.gold -%}
<a href="{{ sponsor.url }}" target="_blank" title="{{ sponsor.title }}"><img src="{{ sponsor.img }}" style="border-radius:15px"></a>
{% endfor -%}
{%- for sponsor in sponsors.silver -%}
<a href="{{ sponsor.url }}" target="_blank" title="{{ sponsor.title }}"><img src="{{ sponsor.img }}" style="border-radius:15px"></a>
{% endfor %}
{% endif %}

<!-- /sponsors -->

<a href="https://fastapi.tiangolo.com/fastapi-people/#sponsors" class="external-link" target="_blank">Andere Sponsoren</a>

## Meinungen

"_[...] I'm using **FastAPI** a ton these days. [...] I'm actually planning to use it for all of my team's **ML services at Microsoft**. Some of them are getting integrated into the core **Windows** product and some **Office** products._"

<div style="text-align: right; margin-right: 10%;">Kabir Khan - <strong>Microsoft</strong> <a href="https://github.com/tiangolo/fastapi/pull/26" target="_blank"><small>(ref)</small></a></div>

---

"_We adopted the **FastAPI** library to spawn a **REST** server that can be queried to obtain **predictions**. [for Ludwig]_"

<div style="text-align: right; margin-right: 10%;">Piero Molino, Yaroslav Dudin, and Sai Sumanth Miryala - <strong>Uber</strong> <a href="https://eng.uber.com/ludwig-v0-2/" target="_blank"><small>(ref)</small></a></div>

---

"_**Netflix** is pleased to announce the open-source release of our **crisis management** orchestration framework: **Dispatch**! [built with **FastAPI**]_"

<div style="text-align: right; margin-right: 10%;">Kevin Glisson, Marc Vilanova, Forest Monsen - <strong>Netflix</strong> <a href="https://netflixtechblog.com/introducing-dispatch-da4b8a2a8072" target="_blank"><small>(ref)</small></a></div>

---

"_I’m over the moon excited about **FastAPI**. It’s so fun!_"

<div style="text-align: right; margin-right: 10%;">Brian Okken - <strong><a href="https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855" target="_blank">Python Bytes</a> podcast host</strong> <a href="https://twitter.com/brianokken/status/1112220079972728832" target="_blank"><small>(ref)</small></a></div>

---

"_Honestly, what you've built looks super solid and polished. In many ways, it's what I wanted **Hug** to be - it's really inspiring to see someone build that._"

<div style="text-align: right; margin-right: 10%;">Timothy Crosley - <strong><a href="https://www.hug.rest/" target="_blank">Hug</a> creator</strong> <a href="https://news.ycombinator.com/item?id=19455465" target="_blank"><small>(ref)</small></a></div>

---

"_If you're looking to learn one **modern framework** for building REST APIs, check out **FastAPI** [...] It's fast, easy to use and easy to learn [...]_"

"_We've switched over to **FastAPI** for our **APIs** [...] I think you'll like it [...]_"

<div style="text-align: right; margin-right: 10%;">Ines Montani - Matthew Honnibal - <strong><a href="https://explosion.ai" target="_blank">Explosion AI</a> founders - <a href="https://spacy.io" target="_blank">spaCy</a> creators</strong> <a href="https://twitter.com/_inesmontani/status/1144173225322143744" target="_blank"><small>(ref)</small></a> - <a href="https://twitter.com/honnibal/status/1144031421859655680" target="_blank"><small>(ref)</small></a></div>

---

## **Typer**, FastAPI für CLIs

<a href="https://typer.tiangolo.com" target="_blank"><img src="https://typer.tiangolo.com/img/logo-margin/logo-margin-vector.svg" style="width: 20%;"></a>

Wenn du eine Terminal-Applikation programmierst, anstatt einer Web-API, sieh dir <a href="https://typer.tiangolo.com/" class="external-link" target="_blank">**Typer**</a> an.

**Typer** ist FastAPIs kleiner Zwilling. Und es ist gedacht als **FastAPI für CLIs**. ⌨️ 🚀

## Anforderungen

Python 3.6+

FastAPI steht auf den Schultern von Giganten: <!-- Unsure, again, to be more precise: TODO -->

* <a href="https://www.starlette.io/" class="external-link" target="_blank">Starlette</a> für die Web-Teile.
* <a href="https://pydantic-docs.helpmanual.io/" class="external-link" target="_blank">Pydantic</a> für die Daten-Teile.

## Installation

<div class="termy">

```console
$ pip install fastapi

---> 100%
```

</div>
<!-- TODO -->
Du brauchst auch einen ASGI-Server, für "production" wie <a href="https://www.uvicorn.org" class="external-link" target="_blank">Uvicorn</a> oder <a href="https://gitlab.com/pgjones/hypercorn" class="external-link" target="_blank">Hypercorn</a>.

<div class="termy">

```console
$ pip install uvicorn[standard]

---> 100%
```

</div>

## Beispiel

### Kreiere es

* Erstelle eine Datei `main.py` mit:

```Python
from typing import Optional

from fastapi import FastAPI

app = FastAPI()


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: Optional[str] = None):
    return {"item_id": item_id, "q": q}
```

<details markdown="1">
<summary>Oder benutze <code>async def</code>...</summary>

Wenn dein Code `async` / `await` benutzt, benutze `async def`:

```Python hl_lines="9  14"
from typing import Optional

from fastapi import FastAPI

app = FastAPI()


@app.get("/")
async def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
async def read_item(item_id: int, q: Optional[str] = None):
    return {"item_id": item_id, "q": q}
```

**Beachte**:

Wenn du dir nicht sicher bist, lies dir die _"In a hurry?"_-Section über <a href="https://fastapi.tiangolo.com/async/#in-a-hurry" target="_blank">`async` und `await` in der Dokumentation durch.</a>.

</details>

### Starte es

Starte den Server mit:

<div class="termy">

```console
$ uvicorn main:app --reload

INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [28720]
INFO:     Started server process [28722]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
```

</div>

<details markdown="1">
<summary>Über den Befehl <code>uvicorn main:app --reload</code>...</summary>

Der Befehl `uvicorn main:app` bezieht sich auf:

* `main`: Die Datei `main.py` (Das Python "module").
* `app`: Das Objekt erstellt innerhalb der Datei `main.py` in der folgenden Zeile `app = FastAPI()`.
* `--reload`: startet den Server automatisch nach Änderungen neu. Nur während der Entwicklung benutzen.

</details>

### Überprüfe es

Öffne folgenden Link <a href="http://127.0.0.1:8000/items/5?q=somequery" class="external-link" target="_blank">http://127.0.0.1:8000/items/5?q=somequery</a>.

Du wirst die JSON-Antwort wie folgt sehen:

```JSON
{"item_id": 5, "q": "somequery"}
```

Du hast schon eine API erstellt, die:

* HTTP-Anfragen unter den _Pfaden_ `/` und `/items/{item_id}` verarbeitet.
* Beide _Pfade_ nehmen `GET` <em>Operationen</em> (auch bekannt als HTTP _methods_).
* Der _Pfad_ `/items/{item_id}` hat einen _Pfad-Parameter_ `item_id` welcher ein `int` (Zahl) sein soll.
* Der _Pfad_ `/items/{item_id}` hat einen optionalen `str` _Anfragen-Parameter_ `q`.

### Interaktive API-Dokumentation

Jetzt gehe zu <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

Du wirst eine automatische API-Dokumentation sehen (bereitgestellt von <a href="https://github.com/swagger-api/swagger-ui" class="external-link" target="_blank">Swagger UI</a>):

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-01-swagger-ui-simple.png)

### Alternative API-Dokumentation

Und jetzt gehe zu <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

Du wirst eine alternative automatische API-Dokumentation sehen (bereitgestellt von <a href="https://github.com/Rebilly/ReDoc" class="external-link" target="_blank">ReDoc</a>):

![ReDoc](https://fastapi.tiangolo.com/img/index/index-02-redoc-simple.png)

## Beispiel-Upgrade

Jetzt modifiere die Datei `main.py` um einen _Body_ von einer `PUT`-Anfrage anzunehmen.

Deklariere den _Body_ mit Pythons standard-_types_, dank Pydantic.

```Python hl_lines="4  9-12  25-27"
from typing import Optional

from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()


class Item(BaseModel):
    name: str
    price: float
    is_offer: Optional[bool] = None


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: Optional[str] = None):
    return {"item_id": item_id, "q": q}


@app.put("/items/{item_id}")
def update_item(item_id: int, item: Item):
    return {"item_name": item.name, "item_id": item_id}
```

Der Server sollte automatisch neustarten (weil du die `--reload`-Flagge zum `uvicorn`-Befehl von vorhin hinzugefügt hast).

### Interaktive API-Docs Upgrade

Jetzt gehe zu <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

* Die interaktive API-Dokumentation wird automatisch upgedated, auch mit dem neuen Teil von vorhin:

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-03-swagger-02.png)

* Drücke den Knopf "Try it out", er erlaubt dir, direkt mit der API zu interagieren:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-04-swagger-03.png)

* Dann drücke den "Execute"-Knopf, das Benutzerinterface kommuniziert nun mit deiner API, sendet die Parameter, empfängt das Ergebnis und zeigt es dir an:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-05-swagger-04.png)

### Alternative API docs upgrade

Und nun, gehe zu <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

* Die alternative API-Dokumentation wird auch die neuen Anfragen-Parameter und den neune _body_ anzeigen:

![ReDoc](https://fastapi.tiangolo.com/img/index/index-06-redoc-02.png)

### Wiederholung

In summary, you declare **once** the types of parameters, body, etc. as function parameters. 

You do that with standard modern Python types.

You don't have to learn a new syntax, the methods or classes of a specific library, etc.

Einfach standard **Python 3.6+**.

zum Beispiel, ein `int` (Zahl):

```Python
item_id: int
```

oder für ein komplexeres `Item`-Modell:

```Python
item: Item
```

...und mit dieser einfachen Deklaration bekommst du:

* Editor-Unterstützung, unter anderem:
    * Vervollständigung.
    * Type checks. <!-- TODO -->
* Validierung der Daten:
    * Automatische und klare Fehler wenn die Daten ungültig sind.
    * Überprüfung sogar für die vernestesten JSON-Modelle.
* <abbr title="Auch bekannt als: Umwandlung, Umstellung">Konvertierung</abbr> der Eingabe-Daten: Kommen vom Netzwerk und von Python, gelesen von:
    * JSON.
    * Pfad-Parameter.
    * Anfragen-Parameter.
    * Cookies.
    * Headers.
    * Forms.
    * Dateien.
* <abbr title="Auch bekannt als: Umwandlung, Umstellung">Konvertierung</abbr> der Ausgabe-Daten: Umwandlung von Python-Daten und Typen zu Netzwerk-Daten (wie JSON):
    * Wandle Python-Typen (`str`, `int`, `float`, `bool`, `list`, etc) um.
    * `datetime` Objekte.
    * `UUID` Objekte.
    * Datenbank-Modelle.
    * ...und viele Mehr.
* Automatische interaktive API-Documentation, mit 2 Benutzeroberflächen:
    * Swagger UI.
    * ReDoc.

---

Um auf das vorherige Codebeispiel zurückzukommen, wird **FastAPI**:

* Überprüft dass da ein `item_id` im Pfad von den `GET` und `PUT`-Anfragen ist.
* Überprüft, dass `item_id` ein `int` für `GET` und `PUT`-Anfragen ist.
    * Wenn diese Überprüfung fehlschlägt, sieht der Client einen klaren, verständlichen Fehler.
* Überprüft ob der optionale Parameter `q` (wie in `http://127.0.0.1:8000/items/foo?q=somequery`) für `GET`-Anfragen existiert.
    * As the `q` parameter is declared with `= None`, it is optional.
    * Without the `None` it would be required (as is the body in the case with `PUT`).
* For `PUT` requests to `/items/{item_id}`, Read the body as JSON:
    * Check that it has a required attribute `name` that should be a `str`. 
    * Check that it has a required attribute `price` that has to be a `float`.
    * Check that it has an optional attribute `is_offer`, that should be a `bool`, if present.
    * All this would also work for deeply nested JSON objects.
* Convert from and to JSON automatically.
* Document everything with OpenAPI, that can be used by:
    * Interactive documentation systems.
    * Automatic client code generation systems, for many languages.
* Provide 2 interactive documentation web interfaces directly.

---

We just scratched the surface, but you already get the idea of how it all works.

Try changing the line with:

```Python
    return {"item_name": item.name, "item_id": item_id}
```

...von:

```Python
        ... "item_name": item.name ...
```

...zu:

```Python
        ... "item_price": item.price ...
```

...and see how your editor will auto-complete the attributes and know their types:

![editor support](https://fastapi.tiangolo.com/img/vscode-completion.png)

For a more complete example including more features, see the <a href="https://fastapi.tiangolo.com/tutorial/">Tutorial - User Guide</a>.

**Spoileralarm**: Das Tutorial - user guide includes:

* Declaration of **parameters** from other different places as: **headers**, **cookies**, **form fields** and **files**.
* How to set **validation constraints** as `maximum_length` or `regex`.
* A very powerful and easy to use **<abbr title="also known as components, resources, providers, services, injectables">Dependency Injection</abbr>** system.
* Security and authentication, including support for **OAuth2** with **JWT tokens** and **HTTP Basic** auth.
* More advanced (but equally easy) techniques for declaring **deeply nested JSON models** (thanks to Pydantic).
* Many extra features (thanks to Starlette) as:
    * **WebSockets**
    * **GraphQL**
    * extremely easy tests based on `requests` and `pytest`
    * **CORS**
    * **Cookie Sessions**
    * ...and more.

## Performance

Independent TechEmpower benchmarks show **FastAPI** applications running under Uvicorn as <a href="https://www.techempower.com/benchmarks/#section=test&runid=7464e520-0dc2-473d-bd34-dbdfd7e85911&hw=ph&test=query&l=zijzen-7" class="external-link" target="_blank">one of the fastest Python frameworks available</a>, only below Starlette and Uvicorn themselves (used internally by FastAPI). (*)

To understand more about it, see the section <a href="https://fastapi.tiangolo.com/benchmarks/" class="internal-link" target="_blank">Benchmarks</a>.

## Optional Dependencies

Benutzt von Pydantic:

* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - für schnelleres JSON <abbr title="converting the string that comes from an HTTP request into Python data">"verarbeiten"</abbr>.
* <a href="https://github.com/JoshData/python-email-validator" target="_blank"><code>email_validator</code></a> - for email-Überprüfung.

Benutzt von Starlette:

* <a href="https://requests.readthedocs.io" target="_blank"><code>requests</code></a> - Erforderlich wenn du den `TestClient` benutzen willst.
* <a href="https://github.com/Tinche/aiofiles" target="_blank"><code>aiofiles</code></a> - Erforderlich wenn du `FileResponse` oder `StaticFiles` benutzen willst.
* <a href="https://jinja.palletsprojects.com" target="_blank"><code>jinja2</code></a> - Erforderlich wenn du die Standard-Template-Konfiguration benutzen möchtest.
* <a href="https://andrew-d.github.io/python-multipart/" target="_blank"><code>python-multipart</code></a> - Erforderlich wenn du "Forms" unterstützen willst (<abbr title="converting the string that comes from an HTTP request into Python data">"verarbeitet"</abbr> die "Form" mit `request.form()`).
* <a href="https://pythonhosted.org/itsdangerous/" target="_blank"><code>itsdangerous</code></a> - Erforderlich für `SessionMiddleware`-Unterstützung.
* <a href="https://pyyaml.org/wiki/PyYAMLDocumentation" target="_blank"><code>pyyaml</code></a> - Erforderlich für Starlettes `SchemaGenerator`-Unterstützung (du wirst es wahrscheinlich nicht brauchen).
* <a href="https://graphene-python.org/" target="_blank"><code>graphene</code></a> - Erforderlich für `GraphQLApp`-Unterstützung.
* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - Erforderlich wenn du `UJSONResponse` benutzen möchtest.

Benutzt von FastAPI / Starlette:

* <a href="https://www.uvicorn.org" target="_blank"><code>uvicorn</code></a> - Für den Server, der deine Applikation lädt.
* <a href="https://github.com/ijl/orjson" target="_blank"><code>orjson</code></a> - Erforderlich wenn du  `ORJSONResponse` benutzen möchtest.

Du kannst alle installieren mit `pip install "fastapi[all]"`.

## Lizene

Dieses Projekt steht unter den Bedingungen der MIT-Lizenz.
