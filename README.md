# Copilot security: EDP, labels, and policies

A fictional practice workbook for the Stringfest Analytics article:
https://stringfestanalytics.com/copilot-shield-colors-edp-sensitivity-labels/

The article is being prepared as a draft. Files: copilot-security-demo.xlsx and practice-prompts.txt. No macros or code are required. All names, companies, email addresses, and amounts are invented; email addresses use .example.

## Workbook exercise

Save a working copy to your approved work OneDrive or SharePoint location, then open it in Excel for the web. Open Copilot, choose Chat only, and run the workbook prompt. This route was verified on November 21, 2026. Excel desktop reported a connection error in the author's test, so the illustrated baseline uses Excel for the web.

Check 12 deals and $212,000 total: Proposal 4 / $76,500; Qualified 3 / $48,000; Won 3 / $68,500; Lost 2 / $19,000. Cell F2 independently sums the amounts.

## Optional classification comparison

If IT has supplied a classification-only test label, apply it to the working copy, save, close and reopen, then start a fresh chat and repeat the same prompt. Record the label text and the actual response. The author's newly published demo labels had not yet appeared in Office; this comparison is a suggested check, not a reported test result.

## Browser prompt-protection comparison

Use work-account Microsoft 365 Copilot Chat on the web, starting a new chat for each marker prompt. An administrator must first configure a custom sensitive information type matching STRINGFESTDEMOSECRET20261121 and a Copilot prompt-blocking DLP policy scoped to the test account. The files do not install or enable policies.

Observed in the configured test account: the PUBLIC marker returned 4; the SECRET marker produced an organization-policy restriction while EDP remained displayed. This tests typed prompt text, not uploaded workbook contents or automatic PII detection.

A color alone does not establish which policy applies. Follow your IT team's approved fictional-data testing process.
