BSPD with SCS — MES Racing
Rev 2.0 | Formula Student Rule Compliant
Brake System Plausibility Device with Short Circuit Sense. Opens the shutdown circuit if brake and motor current are simultaneously active for more than 0.5 seconds.
Key ICs

LM293 × 4 — comparators (brake & current thresholds)
NE555 — 0.5s timing
SN74HC27 — fault logic
LM358 — buffering
uA7805 — 5V regulation

Adjustable Thresholds
RV1/RV2 — brake | RV3/RV4/RV5 — current
