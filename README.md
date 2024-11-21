## Sync CBGs shape with voting data
Running the script will sync the CBGs shapefile with voting data and save the result to a new shapefile.

#### Data Sources

- [TIGER/Line Shapefiles](https://www2.census.gov/geo/tiger/TIGER2020PL/STATE/06_CALIFORNIA/06/) - Official census block group shapefiles
- [Dave's Redistricting](https://github.com/dra2020/vtd_data/blob/master/2020_VTD/CA/Demographic_Data_CA.v04.zip) - Census block group voting data compiled by Dave's Redistricting site


## Setup

### 1. Clone the repository
```bash
git clone <https://github.com/Quantifying-Gerrymandering/sync-cbg-shape-with-voting.git>
cd <sync-cbg-shape-with-voting>
```
### 2. Create and activate virtual environment
Windows
```bash
python -m venv venv
venv\Scripts\activate
```
macOS/Linux
```bash
python -m venv venv
source venv/bin/activate
```
### 3. Install dependencies
```bash
pip install -r requirements.txt
```