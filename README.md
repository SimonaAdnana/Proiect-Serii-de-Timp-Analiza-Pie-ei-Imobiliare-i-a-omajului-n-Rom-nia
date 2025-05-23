# Proiect-Serii-de-Timp-Analiza-Pietei-Imobiliare-si-a-somajului-in-Romania
Acest proiect academic analizează două serii de timp esențiale pentru economia României: indicele prețurilor proprietăților rezidențiale și șomajul în rândul persoanelor cu studii universitare. Proiectul este realizat în cadrul Facultății de Administrație și Afaceri, Universitatea din București.

🔍 Obiective
Analiza tendinței și sezonalității pieței imobiliare (2009–2024) folosind medii mobile, coeficienți sezonieri și prognoze pe termen scurt.

Modelare econometrică a șomajului în rândul absolvenților de studii superioare folosind teste de staționaritate (ADF), identificarea modelului ARIMA și realizarea de prognoze.

🛠 Tehnologii și metode utilizate
Limbajul R și pachetele forecast, tseries, urca, pastecs

Analiză de tip:

Decompoziție aditivă a seriilor

Estimarea trendului liniar

Teste ADF pentru verificarea staționarității

Modelare ARIMA cu auto.arima()

Prognoze cu forecast()

📈 Rezultate
Pentru piața imobiliară, s-a identificat o structură aditivă și s-a obținut ecuația trendului: T = 80.7715 + 0.5876*t.

Pentru șomajul în rândul absolvenților, s-a obținut un model ARIMA(1,0,1), confirmând o componentă autoregresivă și staționarizarea seriei prin diferențiere.

📚 Surse de date
FRED: QRON628BIS

INS: Tempo Online

👩‍💻 Autor
Simona Adnana Anghelina
Coordonator: Prof. univ. dr. Mihaela Simionescu

