# Stock Analysis Workbench — historical demo

Explore the demo at https://philipber99.github.io/stock-gui-demo/.

This repository contains the compiled browser demo and its fixed historical
sample dataset. The site runs entirely from static files.

- Stock universe: S&P 100 (101 securities, including share classes).
- Market snapshot: November 12, 2026, at the session close.
- Trend snapshot: TrendSelector v0.1, November 12, 2026, at 12:55 p.m. Pacific.
- Trend results: 84 securities have usable channel predictions; 17 report
  unavailable required model inputs. Unsupported outputs remain unavailable.
- Channel selection, charts, screeners, and navigation work with the saved data.
- Source timestamps and missing-data states are preserved. Some market and
  sector analytics were captured at export time; this is a demonstration
  dataset rather than a point-in-time backtesting dataset.

The data files and saved prediction outputs are part of the public demo.
Model weights, datasource credentials, and production configuration are not
included in this publishing repository.

The editable application is maintained separately. Releases replace the
compiled files here after local build and validation.
