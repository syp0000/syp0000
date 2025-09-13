<!-- Terminal-style block -->
<div align="center">
  <svg width="860" height="420" viewBox="0 0 860 420" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="terminal">
    <!-- Window frame -->
    <defs>
      <linearGradient id="grad" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#2b2f3a"/>
        <stop offset="100%" stop-color="#1f232b"/>
      </linearGradient>
      <filter id="shadow" x="-10%" y="-10%" width="120%" height="120%">
        <feDropShadow dx="0" dy="4" stdDeviation="6" flood-color="#000" flood-opacity="0.25"/>
      </filter>
    </defs>

    <!-- Outer rounded panel -->
    <rect x="10" y="10" rx="16" ry="16" width="840" height="400" fill="url(#grad)" filter="url(#shadow)"/>

    <!-- Header bar -->
    <rect x="10" y="10" rx="16" ry="16" width="840" height="44" fill="#2f3641"/>
    <!-- macOS dots -->
    <circle cx="34" cy="32" r="7" fill="#ff5f57"/>
    <circle cx="58" cy="32" r="7" fill="#ffbd2e"/>
    <circle cx="82" cy="32" r="7" fill="#28c840"/>
    <!-- Title -->
    <text x="420" y="36" text-anchor="middle" fill="#cbd5e1" font-size="14" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace">/siyeon — bash</text>

    <!-- Terminal body -->
    <rect x="10" y="54" width="840" height="356" fill="#0f1217"/>

    <!-- Code text -->
    <g font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace" font-size="15" fill="#e5e7eb">
      <text x="30" y="84" fill="#a3e635">/siyeon $</text>
      <text x="120" y="84">cat skills.py</text>

      <text x="30"  y="112">{</text>
      <text x="60"  y="136">"type": "hard skills",</text>
      <text x="60"  y="160">"categories": [</text>

      <text x="90"  y="184">{</text>
      <text x="120" y="208">"name": "Languages",</text>
      <text x="120" y="232">"items": ["Python", "R", "SQL", "JavaScript", "Java", "C/C++"]</text>
      <text x="90"  y="256">},</text>

      <text x="90"  y="280">{</text>
      <text x="120" y="304">"name": "Data Engineering",</text>
      <text x="120" y="328">"items": ["Supabase", "PySpark", "HBase", "Airflow", "Docker", "SLURM"]</text>
      <text x="90"  y="352">},</text>

      <text x="90"  y="376">{</text>
      <text x="120" y="400">"name": "GIS", "items": ["QGIS", "QField", "GeoPandas", "Folium"]</text>
      <text x="90"  y="424"></text>
    </g>

    <!-- Close brackets (placed a bit lower) -->
    <text x="30" y="404" fill="#e5e7eb" font-size="15" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace">]</text>
    <text x="30" y="428" fill="#e5e7eb" font-size="15" font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace">}</text>
  </svg>
</div>
