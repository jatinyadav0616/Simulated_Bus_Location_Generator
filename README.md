# Simulated_Bus_Location_Generator
Simulated Bus Location Generator is a Python project that creates and updates random GPS locations for 5 buses every 5 seconds, saving their positions in a JSON file. It’s ideal for learning automation, file I/O, and data generation. Easily extensible for more buses or custom location ranges. 


  ## Features

- **Random location generation:** For 5 buses in a specified area.
- **Live updates:** Location data refreshed every 5 seconds.
- **JSON output:** Easy integration with other apps or visualization tools.

## Setup & Usage

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/bus-location-generator.git
   cd bus-location-generator
   ```

2. **Run the script:**
   ```bash
   python src/bus_location_generator.py
   ```

3. **Check bus_locations.json** for the latest simulated positions.

## Folder Structure

```
bus-location-generator/
│
├── src/
│   └── bus_location_generator.py
│
├── bus_locations.json
├── README.md
└── screenshots/
```

## Example Output

```json
{
    "Bus_202": {"lat": 28.4621, "lon": 77.0652},
    "Bus_203": {"lat": 28.4194, "lon": 77.0702},
    "Bus_204": {"lat": 28.4896, "lon": 77.0931},
    "Bus_205": {"lat": 28.4281, "lon": 77.0228},
    "Bus_206": {"lat": 28.4753, "lon": 77.0345}
}
```

 
## License

MIT
