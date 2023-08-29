# webAssembly-bachelor

## Exposee:

### Problemstellung

Das Thema dieser Bachelorarbeit befasst sich mit der Entwicklung und Implementierung von Schnittstellen für Sensoren in WebAssembly. Dabei wird die WebAssembly Micro Runtime (WASMR) als Grundlage genutzt, die eine umfangreiche Sammlung von Tools und Bibliotheken bereitstellt, um WebAssembly in verschiedene Projekte zu integrieren und umzusetzen.

Die Implementierung von Schnittstellen in WebAssembly erfolgt mithilfe des Component-Modells. Hierbei steht das Wasm Interface Type (WIT) Format zur Verfügung, mit dem Pakete erstellt werden können, die Typen, Interfaces und Komponenten definieren und beschreiben. Diese Pakete können sowohl von anderen Modulen importiert als auch exportiert werden.

### Vorgehensweise

Der Arbeitsablauf gliedert sich in zwei Hauptphasen:

* **Integration von WASMR**: Zu Beginn wird WASMR erfolgreich in das Projekt integriert, um die Grundlage für die WebAssembly-Implementierung zu schaffen.
* **Entwicklung von Sensorenschnittstellen**: Anschließend werden mithilfe des WIT-Formats die Schnittstellen für die Sensoren gemäß den spezifischen Anforderungen entwickelt und umgesetzt.

Die entwickelten Schnittstellen werden anschließend getestet. Hierzu kann beispielsweise ein Gerät mit Arduino gebaut werden, um die erstellten Interfaces für Sensoren zu testen, beispielsweise Licht- und Bewegungssensoren.
 
### Evaluation

Die Abschlussphase des Projekts beinhaltet eine detaillierte Evaluation, bei der die Entwicklung und Umsetzung analysiert wird. In dieser Analyse werden die erfolgreichen Aspekte der Entwicklung sowie die Vorteile der Verwendung von WebAssembly herausgestellt.

Zudem werden auftretende Probleme und Herausforderungen dokumentiert. Diese können möglicherweise durch Verbesserungsvorschläge und Lösungsansätze ergänzt werden, um das Projekt weiter zu optimieren.

Links:

Unsere präferierte Runtime: 
* https://github.com/bytecodealliance/wasm-micro-runtime
* https://github.com/WebAssembly/component-model/blob/main/design/mvp/WIT.md
* https://github.com/WebAssembly/component-model/tree/main
