# CALL_FLOW06_Genesys_Multilanguage_IVR-Auto_Language_Selection_API
# Overview: This project demonstrates an enterprise-level multilingual IVR implementation in Genesys Cloud Architect. 
# The call flow automatically detects the caller's country using an external number lookup API and dynamically selects the appropriate language.


# Genesys Multilanguage IVR – Auto Language Selection

## Features
- Automatic language selection based on caller country
- Integration with external Lookup API (Twilio)
- Default language fallback
- Language-aware routing to Tech Support and Sales teams
- Scalable design for adding more languages

## Call Flow Logic
1. Incoming call received in Genesys Cloud
2. Caller number (ANI) extracted
3. External Lookup API used to identify caller country
4. Language selected based on country code:
   - US → English
   - IN → Hindi
   - Others → Default English
5. Call routed to department menu
6. Call transferred to Tech Support or Sales in selected language

## Tools & Technologies
- Genesys Cloud CX
- Genesys Architect
- Data Actions
- External Number Lookup API (Twilio)
- draw.io (diagrams.net)

## Future Enhancements
- API failure handling
- Country-to-language mapping table
- Support for additional languages
- CRM-based language preference lookup

## Disclaimer
This project is for learning and demonstration purposes only.


