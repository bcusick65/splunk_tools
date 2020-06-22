# 20200603 BJC



# Prerequisites
1. Security Essentials v3.1.1+
2. Enterprise Security 5.2+
3. Ensure the use_cases lookup from SSE is shared 'globally'.

# Release notes
## 20200603 BJC
- Initial add of MITRE ATT&CK Risk-Based Alerting content
## 20200612 BJC
- The Out-of-the-Box content lookup values are currently hardcoded. This will be made dynamic next release.
- Added aggregate-based alert count to dashboard
- Updated drilldown searches to enable raw data view
## 20200622 BJC
- Out-of-the-Box content lookups are now dynamic.


# USAGE INSTRUCTIONS
1. Follow associated guide in the accompanying powerpoint deck.
2. Run data inventory check in Splunk Security Essentials (SSE).
3. Enable ES integration under "Configuration" nav bar item in SSE.
4. Run "Content Introspection" under "Data" nav bar item in SSE.
5. Install mitre_attack_overview.xml dashboard within the SSE app context.
