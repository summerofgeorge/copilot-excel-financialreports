# FinancialReports in Copilot for Excel

The hands-on example for the Stringfest Analytics guide, "What are plugins in Copilot for Excel, and what do they do?"

FinancialReports is used because public filings make the connection and tool calls easy to demonstrate and check without a company's private systems. Ordinary Copilot web search may find the same public figures; this exercise illustrates how a plugin works, not why every public-data lookup needs one. Other integrations may add specialized tools, authorized private data or supported actions.

## Files

- `financialreports-practice.xlsx`: a blank, formatted practice table and source fields on the Analysis sheet.
- `prompts.txt`: the two copy-ready prompts and checks.

## Follow along

1. Open the workbook in Excel desktop and save your own working copy to OneDrive or SharePoint. The walkthrough was tested in Windows Excel desktop on November 22, 2026, using the Copilot pane with Allow editing.
2. Open Copilot. Under its three-dot menu, choose Manage plugins, add FinancialReports if necessary, and complete its Connect/sign-in flow. Availability depends on your Copilot experience, account and organization. FinancialFilings, the underlying service, documents a free account and a limited free usage allowance: https://financialfilings.com/integrations/microsoft-copilot/ and https://financialfilings.com/mcp/ . A free provider account does not supply a Microsoft Copilot license.
3. In the prompt composer, choose + > Choose plugins, search for FinancialReports, and select the actual menu result. Confirm the blue FinancialReports chip; do not just type its name.
4. Run prompt 1, inspect the tool activity and source, then run prompt 2 in the same conversation. Review any permission requests for the actual tools and data involved.
5. Check the figures against Microsoft's annual report: https://www.microsoft.com/investor/reports/ar25/index.html . Inspect the formulas and test recalculation. The exercise retrieves public data; it does not demonstrate private-system access or promise a refreshable query or scheduled workflow.

The starter deliberately contains no completed results. Source documents remain with their publishers. Copilot's layout and wording can vary, so inspect what your run actually creates.

By George Mount, Stringfest Analytics: https://stringfestanalytics.com/

Free full course, no account required: https://www.linkedin.com/learning/excel-with-copilot-ai-driven-data-analysis/welcome-to-copilot-and-ai-powered-excel
