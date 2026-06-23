# MI Incremental Attributes - Technical Documentation

📖 **Comprehensive technical design documentation for Incremental Attributes and Partial Success support for Marketing Intelligence (MI) Connectors via Data Connectors Framework (DCF)**

## 🌐 View Documentation

**[Open Documentation Site](https://alonhaze7.github.io/DayZero/)**

## 📋 Overview

This repository contains the complete technical design documentation for implementing extraction progress reporting and partial success support for MI connectors in Salesforce's Data Cloud platform.

### Key Features

- ✅ **Structured Connector Support** - Opt-in configuration for partial success reporting
- ✅ **New DataProvider API** - Enhanced interface for progress tracking
- ✅ **UI Integration** - Visual indicators for partial success states
- ✅ **Fast Retry Recovery** - Skip completed partitions during retries
- ✅ **Comprehensive Documentation** - Multi-page interactive documentation

## 📚 Documentation Sections

1. **Overview** - Executive summary and key features
2. **Requirements** - Detailed requirements and scope
3. **Technical Proposal** - Implementation design
   - Opt-In Configuration
   - DataProvider API
   - Persistence Layer
   - UI Integration
4. **Attribute Lifecycle** - Complete lifecycle of incremental extract attributes
5. **Unstructured Connectors** - Existing partial ingest flow
6. **UI Details** - Frontend implementation details
7. **Database Changes** - Proposed schema updates
8. **References** - Related documents and resources

## 🚀 Features

- **Interactive Navigation** - Side navigation with smooth scrolling
- **Search Functionality** - Full-text search across all documentation
- **Collapsible Sections** - Expandable detailed information
- **Code Syntax Highlighting** - Easy-to-read code examples
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Modern UI** - Clean, professional Salesforce-inspired design

## 📝 Original Source

Based on the design document created by **@Rupa Singh** (rupa.singh@salesforce.com) on June 15th, 2026.

- [Original Google Doc](https://docs.google.com/document/d/16wgk49mFcZBot_miPZQ3Zc3evoCzHWzqE68qJurIB50/edit?tab=t.0)

## 🔗 Related Resources

### Design Documents
- [HLD: Detailed Extraction Progress for Data Cloud Connectors](https://docs.google.com/document/d/17jI4E0EoXMx4JKeS8t-k31PKMDRyGs83NR0LTs85n-o/edit?tab=t.0#heading=h.p7au6x9xmu66)
- [[262] Partial Ingest for structured connectors](https://docs.google.com/document/d/19jkyk1PagTmD-W5ViRue8Upv8H9Ak25Kh2rWg1n6nM0/edit?tab=t.0#heading=h.h8z3k4fipuhj)
- [[260] Partial Ingest & Guardrails support for Unstructured Connectors](https://docs.google.com/document/d/17E3m1Pl5JKY_DgXTGsRJzSGG0a636uNsKwiUl9tqR1I/edit?tab=t.0)

### GUS Items
- [TD-0323935](https://gus.lightning.force.com/lightning/r/ADM_Team_Dependency__c/a0nEE000001G00HYAS/view) - DCF Team Dependency
- [TD-0323936](https://gus.lightning.force.com/lightning/r/ADM_Team_Dependency__c/a0nEE000001G01tYAC/view) - Data Services Team Dependency

## 🛠️ Local Development

To view the documentation locally:

```bash
# Clone the repository
git clone https://github.com/alonhaze7/DayZero.git

# Open index.html in your browser
open index.html
# or
python -m http.server 8000
# Then navigate to http://localhost:8000
```

## 📄 License

This documentation is internal to Salesforce and should not be shared externally.

## 👥 Contributors

- **Original Design**: Rupa Singh (@rupa.singh@salesforce.com)
- **Documentation**: Generated and formatted on June 23, 2026

---

**Last Updated**: June 23, 2026
