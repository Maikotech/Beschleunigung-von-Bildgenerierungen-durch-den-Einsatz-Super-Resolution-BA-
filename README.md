# Beschleunigung-von-Bildgenerierungen-durch-den-Einsatz-Super-Resolution-BA-
Implementierung des in der Bachelorarbeit getesteten Verfahren zur beschleunigten Inferenz auf einem NVIDIA Jetson AGX Orin

##1. Methodik
-Promptübertragung über einen TCP Socket: [HTTP Anfragen an Flask Server] -> [Antwort an TCP Socket]
-Promptübertragung in einem geschlossenem System

-Anschluss des Super Resolution Models: Real ERSGAN

