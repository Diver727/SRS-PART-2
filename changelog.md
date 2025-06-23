```markdown
# Changelog - Campus Accessibility Navigation System

## Timeline of Changes (June 12–23, 2025)

### June 12 - Scope Definition & Stakeholder Alignment
- **Author**: Alimzhan  
- **Changes**:
  - Rewrote Scope section (1.2) to define user roles and capabilities
  - Added administrator functions to Product Overview (1.3.2)
  - Expanded User Characteristics with accessibility details (1.3.3)
- **Impact**: Established clear system boundaries and stakeholder responsibilities
- **Validation**: Approved by project sponsor after review

### June 13 - Requirements Restructuring
- **Author**: Alimzhan  
- **Changes**:
  - Implemented Kano Model classification for all requirements
  - Added traceability IDs (FR-01 to FR-17)
  - Mapped requirements to specific user roles
- **Impact**: Enabled requirement prioritization and test case mapping
- **Validation**: Verified against ISO 29148 traceability matrix

### June 14 - Database Architecture Overhaul
- **Authors**: Alimzhan & Aishah  
- **Changes**:
  - Replaced class diagram with normalized ERD (3.5.1)
  - Added FacilityUpdateLog and EventAttendance entities
  - Defined audit trails for admin actions
- **Impact**: Resolved data conflicts in event tracking
- **Validation**: SQL schema reviewed by database architect

### June 15 - Verification Framework
- **Authors**: Ahmed & GALAL  
- **Changes**:
  - Reorganized verification headings (4.1)
  - Created role-specific test cases (4.1.1–4.1.3)
  - Fixed "Stakeholdes" → "Stakeholders" typo
- **Impact**: Aligned testing with IEEE 29148 verification standards
- **Validation**: QA lead sign-off

### June 16 - Behavioral Modeling & Diagram Rework (Part 1)
- **Authors**: Alimzhan & Ahmed  
- **Changes**:
  - **Redesigned all activity diagrams** for accurate user flow representation
  - Fixed swimlane misalignments in admin workflow diagrams
  - Reviewed use case diagram logic
- **Impact**: Ensured user journeys match diagrammed behavior
- **Validation**: Validated against updated user journey maps

### June 17 - Compliance & References
- **Authors**: GALAL & Aishah  
- **Changes**:
  - Fixed "EEE" → "IEEE" reference typo
  - Grouped references by category (legal, APIs, tools)
  - Added WCAG 2.1 compliance notes
- **Impact**: Improved academic standards compliance
- **Validation**: Legal department review

### June 18 - Performance Benchmarking
- **Author**: Alimzhan  
- **Changes**:
  - Defined quantifiable metrics for NFRs (3.2)
  - Added scalability target (1000 concurrent users)
  - Specified notification latency threshold
- **Impact**: Established testable performance criteria
- **Validation**: Load testing plan developed

### June 19 - Usability Standards
- **Author**: Alimzhan  
- **Changes**:
  - Added WCAG 2.1 Level AA targets (UR-02)
  - Defined 3-tap navigation rule (UR-03)
  - Created persistent preference requirement (UR-06)
- **Impact**: Formalized accessibility compliance
- **Validation**: Accessibility audit scheduled

### June 20 - Final Diagram Rework (Part 2)
- **Authors**: Aishah & GALAL  
- **Changes**:
  - **Regenerated all diagrams** for consistency and clarity
  - **Standardized diagram numbering and labeling** across document
  - Fixed Data Sync diagram labels
- **Impact**: All diagrams meet visual and technical accuracy standards
- **Validation**: UX team approval

### June 21 - Risk Management
- **Authors**: Ahmed & Aishah  
- **Changes**:
  - Reworded Assumptions with conflict analysis (5.1.1)
  - Clarified third-party API dependencies
  - Added GDPR/PDPA compliance notes
- **Impact**: Documented mitigation strategies
- **Validation**: Risk register updated

### June 22 - Verification Refinement
- **Author**: Aishah  
- **Changes**:
  - Standardized formatting in test cases
  - Fixed font inconsistencies in Section 4
  - Removed redundant diagram (3.5)
- **Impact**: Improved testability and formatting consistency
- **Validation**: Test manager review

### June 23 - Consolidation & Diagram Finalization (Part 3)
- **Authors**: All team members  
- **Changes**:
  - Cross-validated requirement traceability
  - Verified diagram-reference alignment
  - **Conducted final diagram audit** to confirm outdated visuals were fully replaced
  - Standardized document formatting globally
- **Impact**: Version 1.0 baseline established with fully verified diagrams
- **Validation**: Configuration control board sign-off

## Key Improvements
1. **Diagram Accuracy & Standardization**
   - All incorrect/outdated diagrams replaced through multiple coordinated phases
   - Visual consistency improved through collaborative reviews (June 16, 20, 23)

2. **Traceability Matrix**
   - 100% requirements mapped to verification tests
   - Kano classification enables release planning

3. **Compliance Framework**
   - WCAG 2.1 AA accessibility targets
   - GDPR/PDPA data protection measures

4. **Technical Clarifications**
   - Normalized database schema
   - Quantified performance thresholds
   - Resolved entity relationship conflicts

5. **Stakeholder Alignment**
   - Clear role-based capabilities
   - Administrator workflow definitions
   - Accessibility-first navigation design
```
