mkdir -p /mnt/user-data/outputs && cat > /mnt/user-data/outputs/research.md << 'EOF'
---
title: 'Research'
date: 2026-09-22
type: landing

sections:
  - block: markdown
    content:
      title: ''
      text: |-
        <style>
          .rs-wrap { width: min(1000px, 92vw); max-width: none; position: relative; left: 50%; transform: translateX(-50%); }
          .rs-section { margin: 0 0 2.5rem 0; }
          .rs-heading { font-size: 1.6rem; font-weight: 700; font-style: italic; margin: 0 0 0.3rem 0; }
          .rs-rule { border: 0; border-top: 1px solid currentColor; opacity: 0.2; margin: 0 0 1.4rem 0; }
          .rs-item { margin: 0 0 1.6rem 0; }
          .rs-title { font-size: 1.12rem; font-weight: 600; line-height: 1.4; margin: 0 0 0.2rem 0; }
          .rs-title a { color: inherit !important; text-decoration: none !important; }
          .rs-title a:hover { text-decoration: underline !important; }
          .rs-meta { font-size: 0.95rem; opacity: 0.8; margin: 0 0 0.15rem 0; }
          .rs-venue { font-weight: 700; font-style: italic; }
          .rs-link { font-size: 0.85rem; font-weight: 600; text-decoration: none !important; white-space: nowrap; }
          .rs-link:hover { text-decoration: underline !important; }
        </style>
        <div class="rs-wrap">
        <div class="rs-section">
        <h2 class="rs-heading">Publications</h2>
        <hr class="rs-rule">
        <div class="rs-item">
        <div class="rs-title"><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5244436" target="_blank" rel="noopener">Local Favoritism in State Formation</a></div>
        <div class="rs-meta">with Se Yan and Zhengkai Yang</div>
        <div class="rs-meta">Forthcoming at <span class="rs-venue">Journal of Economic History</span> · <a class="rs-link" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5244436" target="_blank" rel="noopener">SSRN ↗</a></div>
        </div>
        </div>
        <div class="rs-section">
        <h2 class="rs-heading">Working Papers</h2>
        <hr class="rs-rule">
        <div class="rs-item">
        <div class="rs-title"><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6841238" target="_blank" rel="noopener">Buying Stability: Civil Service Quotas and Elite Co-optation in Imperial China</a></div>
        <div class="rs-meta">with Se Yan</div>
        <div class="rs-meta">July 2026 · Under Review · <a class="rs-link" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6841238" target="_blank" rel="noopener">SSRN ↗</a></div>
        </div>
        <div class="rs-item">
        <div class="rs-title"><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6851699" target="_blank" rel="noopener">The Daughters of Disaster: Famine, Gender Preferences, and Cohort Sex Ratios in China</a></div>
        <div class="rs-meta">May 2026 · Reject and Resubmit at <span class="rs-venue">Journal of Population Economics</span> · <a class="rs-link" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6851699" target="_blank" rel="noopener">SSRN ↗</a></div>
        </div>
        <div class="rs-item">
        <div class="rs-title">Disaster Legacies and Financial Risk-Taking</div>
        <div class="rs-meta">with Wenbo Jia, Zhengkai Yang, and Se Yan</div>
        <div class="rs-meta">August 2026 · Under Review</div>
        </div>
        </div>
        </div>
    design:
      columns: '1'
---
EOF
