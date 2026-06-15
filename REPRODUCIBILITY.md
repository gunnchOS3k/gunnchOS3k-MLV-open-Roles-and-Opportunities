        # Reproducibility — gunnchOS3k MLV Open Roles

        ## Clone / setup / run

        ```bash
        git clone https://github.com/gunnchOS3k/{name}.git
cd gunnchOS3k-MLV-open-Roles-and-Opportunities
# See README.md for repo-specific setup
python3 scripts/check_required_files.py
# Expected: CI smoke pass; tests pass or documented skip
        ```

        ## Expected outputs

        - Required documentation files present (`python3 scripts/check_required_files.py`)
        - Tests pass **or** documented smoke-only path for docs-only repos
        - No claim of field deployment from synthetic outputs alone

        ## Tool versions

        | Tool | Version guidance |
        |------|------------------|
        | Python | 3.10+ where `requirements.txt` exists |
        | Node | 18+ LTS where `package.json` exists |
        | Make | GNU Make where `Makefile` exists |

        Record exact versions in PR / release notes when publishing.

        ## Fresh machine checklist

        - [ ] Clone repo
        - [ ] Create clean venv / `npm ci`
        - [ ] Run `scripts/check_required_files.py`
        - [ ] Run test command from README
        - [ ] Compare outputs to `results/` or CI logs
        - [ ] Log environment in `reproducibility/FRESH_MACHINE_LOG.md` (optional)

        ## Evidence discipline

        **Real today:** Role descriptions, contribution pathways

        **Synthetic / demo-only:** Hiring pipeline placeholders

        **Planned:** Mentor matching system

        **Not claimed:** Paid employment guarantees
