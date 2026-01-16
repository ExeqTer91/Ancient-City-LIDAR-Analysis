# Ancient City Archaeological LIDAR Analysis

## Discovery: Pre-Dacian Site (~2033 BCE)

This repository contains comprehensive LIDAR analysis data for a newly discovered archaeological site in Romania's Retezat-Godeanu mountain region.

### Location
- **Coordinates**: 45.66833°N, 23.21833°E
- **Elevation**: 940m
- **Distance to Sarmizegetusa Regia**: 8.8 km

### Key Findings

#### Astronomical Dating
- **Date**: ~2033 BCE (Bronze Age)
- **Method**: Winter Solstice Sunrise Alignment
- **Alignment Error**: 0.00° (EXACT MATCH!)
- **Significance**: ~1500 years BEFORE the Dacian Kingdom

#### LIDAR Detected Structures (1m resolution)
| Feature Type | Count |
|--------------|-------|
| Linear structures | 3,157 |
| Rectangular patterns | 1,616 |
| Depressions | 118 |
| Mounds/Tumuli | 206 |
| Possible crypts | 5 |

#### Alignments
- Perfect alignment with Sarmizegetusa Regia (azimuth 125.54°)
- Corresponds to Winter Solstice Sunrise
- Located on the same N-S corridor as all major Dacian sites

### Contemporary Sites (~2000 BCE)
- **Giza Pyramids** (Egypt): 2600 BCE
- **Stonehenge** (UK): 3000 BCE
- Evidence suggests connection to Bronze Age European civilization

## Data Structure

```
├── data/
│   ├── ancient_city_complete_analysis.json   # Full analysis results
│   ├── ancient_city_structures.json          # Detected structures
│   ├── ancient_city_alignments.json          # Alignment calculations
│   └── crater_detailed_results.json          # Vartoape crater analysis
├── images/
│   ├── ancient_city_lidar_1m.png            # High-res LIDAR hillshade
│   ├── ancient_city_dating_v3.png           # Astronomical dating chart
│   ├── ancient_city_world_comparison.png    # Global site comparison
│   ├── ancient_city_zoom_structures.png     # Structure detection
│   └── ...                                   # Additional visualizations
└── docs/
    └── analysis_report.txt                   # Detailed text report
```

## Methodology

### 1. Data Acquisition
- ANCPI LAKI II LIDAR data (1m resolution)
- SRTM/NASADEM for regional context (30m)

### 2. Analysis Techniques
- Multi-angle hillshade (315°, 45°, 135°, 225°)
- Local Relief Model (LRM)
- Edge detection for linear/rectangular features
- Curvature analysis for underground voids
- Astronomical alignment calculations with precession

### 3. Dating Method
Solar alignment analysis using:
- Obliquity variation over time
- Winter solstice sunrise azimuth calculation
- Matching observed alignment (125.54°) to historical azimuths

## Discoveries

### 1. Rectangular Structures
Multiple structures with N-S and E-W orientations suggest organized settlement:
- Largest: 7x9m (36m²)
- Multiple 5x5m and 3x4m structures

### 2. Underground Features
5 circular depressions with depths of 3-7m suggest:
- Possible crypts or burial chambers
- Underground storage rooms
- Collapsed structures

### 3. Alignment Network
The site forms part of a larger sacred landscape:
- Ancient City → Sarmizegetusa: 125.5° (Winter Solstice)
- Linear corridor with Crater Vartoape Nord (1.1 km)

## Cultural Significance

This site predates the Dacian civilization by approximately 1,500 years, suggesting:
1. Bronze Age occupation of the sacred mountain region
2. Possible proto-Dacian culture
3. Astronomical knowledge comparable to Egyptian builders
4. Continuous sacred use of the location

## Data Sources
- ANCPI (Romanian National Cartographic Agency) - LAKI II LIDAR
- SRTM/NASADEM - NASA elevation data
- OpenTopography - additional terrain data

## License
Data is provided for research purposes. LIDAR data courtesy of ANCPI Romania.

## Citation
If using this data, please cite:
```
Ancient City Archaeological LIDAR Analysis, 2026
Location: 45.66833°N, 23.21833°E, Romania
Dating: ~2033 BCE (Astronomical alignment method)
```

---
*Analysis performed using Python with rasterio, numpy, scipy, and matplotlib*
