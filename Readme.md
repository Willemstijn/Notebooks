Repository of my Jupyter notebook collection.

- [Trading strategy Notebooks](#trading-strategy-notebooks)
- [Probeersels en studies](#probeersels-en-studies)
- [Learning notebooks](#learning-notebooks)
- [Other notebooks](#other-notebooks)
- [Other info](./Other_info.md)

# Trading strategy Notebooks

* [Algorithmic trading strategie met Python](./Trading/Algorytmic_trading_strategy_using_python_in_COLAB.ipynb)  
    Afkomstig van een Youtube video. Simpele strategie op basis van twee moving averages. Goede uitleg van wijze waarop een strategie signalen verkrijgt middels een speciaal ontworpen functie voor in en uitstapsignalen, inclusief prijzen. Functie gebruikt 'flags' voor sigPriceBuy en sigPriceSell. Tevens wordt de strategie in matplotlib geplot om te zien waar deze signalen zich bevinden met markers.
* [Charts voor CandleHoarder website](./Trading/CandleHoarder_charts.ipynb)  
    Notebook met alle charts die ik heb ontwikkeld voor gebruik in mijn lange termijn bitcoin en crypto assets investor website. "Candle Hoarder" is een collectie van scripts die data downloaden naar een database. Vanuit deze database worden charts gegenereerd die gebruikt worden voor investeringsbeslissingen en andere inzichten. Deze bevat gebruikte, maar ook oudere (ongebruikte) charts als voorbeeld. Charts in dit notebook zijn o.a. Mayer multiple, Pi Cycle top & bottom, 350 EMA & fibonacci, Moving averages, Supertrend, Bull/bear suppport band en meer.
* [Bitcoin Fundamentals](./Trading/Bitcoin-Fundamentals.ipynb)  
     Notebook heet zo, maar heeft niet de long term charts. Mer voorbeelden van externe chartin libraries als mplfinance, plotly, finplot en downloaden van gegevens vanuit Yahoo finance.
* [Bitcoin fundamentals COLAB](/Trading/Bitcoin_Fundamentals_COLAB.ipynb)  
    Another notebook with yfinance & pandas_ta for calculating a lot of moving averages and then plotting in a matplotlib chart. This time the notebook indeed has indicators like bull/bear support, mayer, accumulation/distribution, moving averages, pi cycle and more.
* [](./Trading/Bollinger,%20QQE,%20MFI,%20Slowstoch%20strategie%20-%205%20minute.ipynb)  
    Panda's TA strategie waarbij gebruik gemaakt wordt van Bollinger bands, QQE en MFI. Buy condities worden met True / False condities gedaan. Als er meerdere True functies zijn, dan uy signal.
* [Bollinger_Band_strategy_tryout_with_Google_Colab](./Trading/Bollinger_Band_strategy_tryout_with_Google_Colab.ipynb)  
    Google colab sheet. Bollinger bands berekenen en plotten met matplotlib, inclusief gebruik van functie.
* [Gann HILO, Macd 7 Slow Stoch strategy](./Trading/4%20juli%202021%20-%20Gann%20HiLo,%20Supertrend%20en%20MACD%20strategy.ipynb)  
    Simpele strategy met gebruik van pandas_ta.
*  [Supertrend one time signal, QQE met sticky Takeprofit forward fill level](./Trading/Supertrend%20one%20time%20signal,%20QQE%20met%20sticky%20Takeprofit%20forward%20fill%20level.ipynb)  
    Pandas_ta indicatoren. Gebruik maken van een 'sticky TP waarde' bij een buy=True signaal dat als exitpunt dient (close>TP)
* [Ichimoku kinko hyo tryout](./Trading/Ichimoku%20kinko%20hyo%20tryout.ipynb)  
    Pandas_ta Ichimoku Kinko Hyo uitproberen.
* [Gann HiLo, Supertrend en MACD strategy](./Trading/Gann%20HiLo,%20Supertrend%20en%20MACD%20strategy.ipynb)  
     Hilo, macd en supertrend. Deze combinatie van indicatoren lijkt bij backtesten best goed te zijn. Bevat ook matplotlib grafiekje.
* [freqtrade-gannhighlow](./Trading/freqtrade-gannhighlow.ipynb)  
    Eigenlijk een supertrend x3 strategy met Gann Hilo en QQE. Met functie om positie van de trade de bepalen, Take profit point en Stoploss point. Technisch goed maar backtest laat minder goede resultaten zien. Inclusief backtestresultaten!
* [freqtrade-supertrend](./Trading/freqtrade-supertrend.ipynb)  
    Zelf een supertrend indicator maken. Daarna Supertrend x3 code zoals freqtrade gannhighlow.
* [Vulcan_strat_30m](./Trading/Vulcan_strat_30m.ipynb)  
    Simpele strategy die later de Vulcan strategy werd. Met berekening van de hoek (cosinus) van een SMA en gebruik maken van qtpylib.
* [SMA 21 50 crossover op 4H strategie-checkpoint](./Trading/SMA%2021%2050%20crossover%20op%204H%20strategie-checkpoint.ipynb)
    Berekenen van stijgingshoeken van een SMA curve met scipy.spatial.distance cosine.
* [stoch_and_rsi](./Trading/stoch_and_rsi.ipynb)  
    Belangrijkste punt is hier dat met RSI condities gewerkt wordt via numpy. Dat anders werkt dan met een functie.
* [CryptoMaven_strategy](./Trading/Pandas-Ta/CryptoMaven_strategy.html)  
    Oorspronkelijke CryptoMaven trading strategy voor handmatig traden. Met berekenen van moving averages, check op long/short, advice met functie en condities, ATR indicator.
* [Ganning high low strategy in Colab](./Trading/freqtrade-gannhighlow.ipynb)  
    Ganning High low dataframe uitzoeken  middels Google Colab. Tevens wordt QQE uitgezocht en tripple Supertrend. Positie van trade bepaald (if X = 1 , then position = hith_r_long). Entry signaal detectie (celverandering tov. van vorige cel - Goed). Stoploss prijs bepaling met vaste waarde! Takeprofit prijs bepalen met vaste waarde obv. onder/boven supertrend! Met R:R van 1:1,5. Tot slot worden echte backtestresultaten getoont voor deze strategie!
*  [PowerX met stoploss en takeprofit studie](./Trading/Improved_PowerX_strategy_by_DCD.ipynb)  
    Verbeterde PowerX strategie voor DCD channel studie. Dit notebook bevat indicatoren als stoch, macr, rsi, en atr. Het heeft custom buy en sell signalen. Het bevat tevens takeprofit en stoploss punten obv atr die VAST geprogrammeerd zijn. Tot slot een chart met alle indicatoren en buyprijs, takeprofit en stoploss punten weergegeven in een plot. Mooie sheet om als uitgangspunt te dienen voor toekomstige strategie"en!!
*  [PowerX met stoploss en takeprofit studie](./Trading/PowerX_strat_incl_TP_SL_obv_ATR_Freqtrade_ready_by_DCD.ipynb)  
    Een andere versie, nader te bekijken wat hier aan de hand is...

## Probeersels en studies

* [freqtrade-strategy-snippets](./trading/../Trading/freqtrade-strategy-snippets.ipynb)  
     Code snippets voor het bepalen van oa. Highest / Lowest value in array; Tighter stop loss with ATR usage; Indicatoren. 
*  [Pandas_ta_study](./Trading/Pandas_ta_study.ipynb)  
    Een van de eerste jupyter notebooks waarin ik indicatoren uitprobeerde, extra kolommen maakte obv. berekeningen en meer.
* [Custom stoploss in Python for trading](./Trading/Custom%20stoploss%20in%20Python%20for%20trading.ipynb)  
    voorbeelden die ik nageprogrammeerd van een of andere hindi trading channel over custom stoplosses. Ik begrijp er op dit moment de ballen van maar de code werkt en het is mijn streven om te begrijpen wat er aan de hand is en of ik dit kan gebruiken in mijn eigen tradingstrategie"en voor freqtrade.  
* [Bitcoin candles plotten met MPLFinance](./training/../Training/matplotlibbitcoin/MPLFinance.ipynb)  
    Candlesticks produceren met MPL Finance. Geen matplotlib.                                           |

* [MACD strategie in Colab](./Trading/MACD_trading_strategy_in_COLAB.ipynb)  
    Studie over het maken van MACD zonder pandas_ta en het maken van een functie voor instap/uitstap momenten. Tevens wordt alles met matplotlib geplot.
* [MFI strategie in Colab](./Trading/MFI_trading_strategy_in_COLAB.ipynb)  
    Studie voor het maken van MFI indicator en het maken van een functie voor instappen/uitstappen. Ook wordt alles met matplotlib getoont in een chart.
* [CryptoMaven-rediscover](./Trading/CryptoMaven-rediscover.ipynb)  
    Pandas df met gebruik van functies en 'if then' condities. Ook kolom dat aangeeft dat een celwaarde is veranderd tov. vorige waarde. Bepaald signaal voor handmatig instappen.
*  [CryptoMaven2-oversold_strategy](./Trading/CryptoMaven2-oversold_strategy.ipynb)  
    RSI, MFI condities (onder 20). Bevat functies en condities. Bevat ATR indicator voor SL en TP.
*  [CryptoMaven2_strategy](./Trading/CryptoMaven2_strategy.ipynb)  
    ATR, Dema9, SMA21, RSI en MFI signals genereren bij oversold. Incl. functies en condities.
*  [CryptoMaven_strategy](./Trading/CryptoMaven_strategy.ipynb)  
     Oorspronkelijke Telegram trade signals dataframe obv. DEMA 9 > SMA 21  

# Learning notebooks

* [Python-course-notes](./Training/Python-course-notes.ipynb)  
    Uitgebreid en simpel overzicht van basiskennis Python.
* [Numpy-course-notes](./training/../Training/Numpy-course-notes.ipynb)  
    Uitgebreid en simpel overzicht van basiskennis Numpy.
* [Jupyter-courses-notes](./training/../Training/Jupyter-courses-notes.ipynb)  
    Simpel overzichtje van Jupyter commando's.
* [Pandas Data Science Tutorial](./training/../Training/Pandas-data-science-tutorial/.ipynb_checkpoints/Pandas%20Data%20Science%20Tutorial.ipynb)  
    Uitgebreide training hoe een Pokemon Excel te bewerken in Pandas
* [Technical Analysis Library in Python Tutorial](./training/../Training/Technical%20Analysis%20Library%20in%20Python%20Tutorial/Technical%20Analysis%20Library%20in%20Python%20Tutorial.ipynb)  
    Data downloaden met CCTX en vervolgens bewerken in Pandas
* [Jupyter notebook starter](./Training/Jupyter_notebook_starter.html)  
    My [Corey Shafer's "Jupyter notebook tutorial"](https://www.youtube.com/watch?v=HW29067qVWk) notes.

# Other notebooks

* [Python training van STAP](./Misc/Python_stap.ipynb   )
* [Changing Jupyter notebook themes](./Misc/Jupyter_themes.ipynb)
* [Python virtual machine procedure](Misc/Python%20VM%20procedure.ipynb)

# [Other info](./Other_info.md)
