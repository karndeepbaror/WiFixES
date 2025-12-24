# WiFixES – Data Flow

**1. Input:**

   - User provides CLI flags (e.g., `--scan`, `--deep`)

**2. Processing:**

   - Scanner collects network info
   - Analyzer computes stability and health scores

**3. Storage:**

   - Scan history saved in JSON (`WiFixES-Data/scan-history.json`)
   - Optional text report stored (`WiFixES-Data/report.txt`)

**4. Output:**

   - Terminal display (Rich tables)
   - Risk classification & environment summary