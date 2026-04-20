# Apache POI (apache-poi)
Apache POI is a Java API for manipulating various file formats based upon the Office Open XML standards (OOXML) and Microsoft's OLE2 Compound Document format (OLE2). It supports reading and writing Excel, Word, PowerPoint, Visio, and Outlook files.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-poi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-poi/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Document Processing, Excel, Java, Microsoft Office, PowerPoint, Word, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache POI API
POI provides Java APIs for reading and writing Microsoft Office formats including Excel (HSSF/XSSF), Word (HWPF/XWPF), PowerPoint (HSLF/XSLF), Visio (HDGF/XDGF), and Outlook (HSMF), with support for formulas, charts, and formatting.

**Human URL:** [https://poi.apache.org/components/](https://poi.apache.org/components/)

#### Tags:

 - Document Processing, Excel, Java, Apache, Open Source

#### Properties

- [Documentation](https://poi.apache.org/components/)
- [OpenAPI](openapi/apache-poi-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/poi)
- [Documentation](https://poi.apache.org/)
- [SpectralRules](rules/apache-poi-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-poi-vocabulary.yaml)
- [NaftikoCapability](capabilities/poi-workflow.yaml)
- [JSON-LD](json-ld/apache-poi-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Excel HSSF/XSSF | Read and write Excel files in legacy XLS (HSSF) and modern XLSX (XSSF) formats |
| Word HWPF/XWPF | Read and write Word documents in legacy DOC (HWPF) and modern DOCX (XWPF) formats |
| PowerPoint HSLF/XSLF | Create and manipulate PowerPoint presentations in PPT and PPTX formats |
| Formula Evaluation | Evaluate Excel formulas and compute cell values programmatically |
| Streaming API | Low-memory streaming API (SXSSF) for writing large Excel files |
| Chart Support | Create and modify charts in Excel workbooks and PowerPoint slides |
| Digital Signatures | Sign Office documents with digital signatures using OOXML standards |

## Use Cases

| Name | Description |
|------|-------------|
| Report Generation | Generate Excel and Word reports programmatically from application data |
| Data Import/Export | Import data from Excel spreadsheets and export results back |
| Template Processing | Fill Office document templates with dynamic data |
| Document Conversion | Convert between legacy Office formats and modern OOXML formats |

## Integrations

| Name | Description |
|------|-------------|
| Apache Tika | POI is used by Tika for Office document text extraction |
| Spring Framework | Integrate POI with Spring Boot for web-based document generation |
| Maven Central | Available as org.apache.poi artifacts on Maven Central |
| Apache Commons | Uses Commons Collections and Commons Math for data structures |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache POI API](openapi/apache-poi-api.yaml)

### JSON Schema

- [Workbook](json-schema/apache-poi-workbook-schema.json)
- [Sheet](json-schema/apache-poi-sheet-schema.json)
- [Cell](json-schema/apache-poi-cell-schema.json)
- [Document](json-schema/apache-poi-document-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache POI JSON Structures](json-structure/)

### JSON-LD

- [Apache POI Context](json-ld/apache-poi-context.jsonld)

### Examples

- [Apache POI Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Document Processing Workflow](capabilities/poi-workflow.yaml) | Apache POI | 8 | Application Developer, Data Engineer |

## Vocabulary

- [Apache POI Vocabulary](vocabulary/apache-poi-vocabulary.yaml) — Unified taxonomy mapping Microsoft Office document processing resources, actions, workflows, and personas

## Rules

- [Apache POI Spectral Rules](rules/apache-poi-spectral-rules.yml) — Rules enforcing Apache POI API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
