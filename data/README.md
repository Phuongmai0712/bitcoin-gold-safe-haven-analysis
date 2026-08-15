\# Data Sources



This project combines market, uncertainty and macro-financial data from several external sources.



Some market data are downloaded automatically when the notebook runs. Other source datasets are included in the `data/` folder for reproducibility. If a local file is unavailable, it can be downloaded directly from the original provider listed below.



\---



\## Downloaded in the Notebook



The following market series are retrieved through the `yfinance` package:



| Variable | Ticker | Use |

|---|---|---|

| Bitcoin | `BTC-USD` | Alternative asset |

| SPDR Gold Shares | `GLD` | Tradable proxy for gold |

| S\&P 500 | `^GSPC` | Equity benchmark |

| VIX | `^VIX` | Market-stress indicator |

| WTI Crude Oil | `CL=F` | Market control |

| U.S. Dollar Index | `DX-Y.NYB` | Market control |



These series are downloaded automatically when the notebook is run.



\---



\## Local Source Files



The following source files are used by the notebook:



```text

data/

├── US\_EPU\_daily.csv

├── GPR\_daily.csv

├── DGS10.csv

└── SP500Ex7.csv

```

| Data | Source |

|---|---|

| U.S. Economic Policy Uncertainty | \[PolicyUncertainty.com](https://www.policyuncertainty.com/us\_monthly.html) |

| Geopolitical Risk Index | \[Caldara \& Iacoviello GPR](https://www.matteoiacoviello.com/gpr.htm) |

| 10-Year U.S. Treasury Yield (`DGS10`) | \[FRED](https://fred.stlouisfed.org/series/DGS10) |

| S\&P 500 Ex-Magnificent Seven | \[S\&P Dow Jones Indices](https://www.spglobal.com/spdji/en/indices/equity/sp-500-ex-magnificent-7-index/) |

