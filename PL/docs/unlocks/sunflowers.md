# Słoneczniki
[Słoneczniki](objects/sunflower) zbierają moc słońca. Możesz zbierać tę moc.

Sadzenie ich działa dokładnie tak samo jak sadzenie marchewek czy dyń.

Zebranie dojrzałego słonecznika daje moc.
Jeśli na farmie jest co najmniej 10 słoneczników, a ty zbierzesz ten z największą liczbą płatków, otrzymasz `5` razy więcej mocy!

`measure()` zwraca liczbę płatków słonecznika pod dronem.
Słoneczniki mają co najmniej `7` i co najwyżej `15` płatków.
Można je zmierzyć, zanim w pełni urosną.

Kilka słoneczników może mieć taką samą liczbę płatków, więc może być też kilka słoneczników z największą liczbą płatków. W takim przypadku nie ma znaczenia, który z nich zbierzesz.

Dopóki masz moc, dron będzie jej używał, aby poruszać się dwa razy szybciej.
Zużywa 1 jednostkę mocy co 30 akcji (takich jak ruchy, zbiory, sadzenie...)
Wykonywanie innych instrukcji kodu również może zużywać moc, ale znacznie mniej niż akcje drona.

Ogólnie rzecz biorąc, wszystko, co jest przyspieszane przez ulepszenia prędkości, jest również przyspieszane przez moc.
Wszystko, co jest przyspieszane przez moc, zużywa również moc proporcjonalnie do czasu potrzebnego na wykonanie, ignorując ulepszenia prędkości.