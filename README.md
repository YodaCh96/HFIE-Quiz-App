<p align="center">
    <a href="ec2-3-140-189-226.us-east-2.compute.amazonaws.com"><img src="https://capsule-render.vercel.app/api?type=rect&color=009ACD&height=100&section=header&text=HFIE Quiz&fontSize=60%&fontColor=ffffff" alt="website title image"></a>
    <h2 align="center">👉 <a href="https://hfiequiz.herokuapp.com" >WebSeite 👈</a></h2>
    <h2 align="center">👉 Eine HFIE Quiz Applikation in Django 👈</h2>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/language-HTML-blue?style=for-the-badge">
    <img src="https://img.shields.io/badge/language-CSS-blue?style=for-the-badge">
    <img src="https://img.shields.io/badge/language-BootStrap-blue?style=for-the-badge">
    <img src="https://img.shields.io/badge/language-Django-blue?style=for-the-badge">  
</p>

## Ausgangslage

An der HFIE in Zug werden Studenten optimal auf die Arbeitswelt vorbereitet. Mithilfe eines modularen Aufbaus, sowie personalisiertem Lernen, wird den Studenten ermöglicht, sich selbstständig weiterzuentwickeln. 

In dieser Projektarbeit wird eine Quiz-Applikation entwickelt, wo einem Benutzer die Möglichkeit gibt, sein Wissen testen und Fragen von der HFIE-Modulen beantworten zu können. Sobald der Benutzer die Quiz-Applikation startet, werden die verschiedenen Quiz angezeigt. Nach erfolgreicher Anmeldung bzw. Registrierung, kann der Benutzer die verschiedene Quizze auswählen und testen.

## Techniken, Frameworks und Tools

- Programmiersprachen: Python, SQL
- Framework: Django
- Datenbank: SQLite
- Server: Heroku
- Tools: Github

## Hardware

- Persönliche Computer

## Vorkenntnisse 
- Grundwissen in Python, HTML, CSS und JS

## Neue Lerninhalte

- Erstellung einer Applikation mit Django
- Hosting eines Django-Projekts auf Heroku

## Design Pattern

Die HFIE-Quiz-Applikation ist nach dem Model-Template-View (MTV) aufgebaut. MTV orientiert sich am bekannten Model-View-Controller (MVC). Ich entschied mich für dieses MTV Design Pattern, da ich mit Hilfe weniger Zeilen im Code in den Models eine Datenbankstruktur anlegen konnte. Django hat automatisch das SQL für die Erstellung der Tabellen in SQlite erzeugt und hat dann die entsprechenden Tabellen erstellt. Des Weiteren sind die Programmlogiken und statische Daten, bzw. Media-Dateien strikt voneinander getrennt und können zum Beispiel auch auf verschiedenen Servern (z.B. Heroku) liegen. Die Module werden in sogenannten Apps erstellt und sind komplett von der Logik der Hauptanwendung getrennt. All diese Dinge kann ich problemlos und auch individuell anpassen.

## Component Diagram

![Component Diagram](component_diagram.PNG)

## User Stories

Für das Projekt sind folgende User Stories definiert:

- Als Lehrer möchte ich neue Quizze zu erstellen.
- Als Lehrer möchte ich neue Fragen hinzufügen.
- Als Lehrer möchte ich die Möglichkeit haben, die verbleibende Zeit eines Quiz selber zu definieren.
- Als Studierender möchte ich mich für Quizze anmelden können.
- Als angemeldeter Benutzer möchte ich mich auch abmelden können.

## Projektvorgehen

Die Arbeit zielt auf eine spezifische Zielgruppe ab &rarr; Studenten von HFIE.

Damit ich einen groben Überblick zu meiner Arbeit verschaffe, habe ich zu Beginn erstmals ein kurzes Brainstorming durchgeführt, um die einzelnen Komponenten definieren zu können. Für das Projekt musste vor allem für die HFIE-Applikation eine Informationsbeschaffung durchgeführt werden. Die Lösung wurde mithilfe des Django umgesetzt. Mein Ziel war, die HFIE-Quiz-Applikation in kürzerer Zeit vom Konzept bis zur Fertigstellung zu bringen. Aus diesem Grund habe ich als Framework Django gewhählt. Django hat die Entwicklung dieser komplexer und datenbankgestützter Applikation erleichtert. Die Verwaltungsoberfläche von Django hat mir geholfen, Dinge zu erstellen, zu aktualisieren, zu lesen und zu löschen.
