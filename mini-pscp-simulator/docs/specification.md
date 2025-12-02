# Mini-PSCP Simulator — Phase 1 Specification

## Purpose
Mini-PSCP is an educational simulator inspired by the Public Procurement Portal of Catalonia (PSCP).  
Its objective is to provide a minimal, practical environment to learn public procurement concepts through simple contract and bid simulations.

## Scope of Phase 1
Phase 1 focuses on the simplest functional workflow:
1. Create a contract  
2. Add bids from suppliers  
3. List contracts and bids  
4. Compute a basic winner based on lowest price  

## Out of Scope (Phase 1)
- Real legal validation  
- Document management  
- Authentication and identity  
- Electronic signature  
- Advanced award criteria (quality, weighted formulas)  
- Analytics and dashboards  

## Technologies
- **Backend:** FastAPI  
- **Frontend:** Streamlit  
- **Runtime:** GitHub Codespaces  

## Deliverables
- REST API for contract creation and listing  
- REST API for bid submission and listing  
- Minimal Streamlit UI to interact with the API  
- Simple logic to determine the winning bid  
