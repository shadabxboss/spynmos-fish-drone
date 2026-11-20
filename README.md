# SPYNMOS Fish Feeding Drone

> **SPYNMOS: Where Navigation Meets Innovation**

An autonomous aquatic drone concept for aquaculture. It carries fish feed, flies a GPS-guided path over a pond and drops the feed evenly. It can land safely on water if something goes wrong.

This repository holds the concept presentation and the 3D models.

## The problem

- Manual feeding is slow and labour-intensive, especially in large ponds.
- Feed is scattered unevenly, which wastes it and causes unequal fish growth.
- Feeding is risky in bad weather.
- The result is higher costs, more stress and lower yield for farmers.

## How it works

1. **Load** fish feed into the container.
2. **Fly** over the pond on a GPS-guided path.
3. **Drop** the feed evenly with the controlled dropping system.

## Key features

| Feature | What it does |
|---|---|
| **SmartFeed 360 (AquaFeed 360)** | Rotating feeder that releases feed every 5 seconds to spread it evenly across the pond |
| **FloatX (AquaShield)** | Boat-style attachment that keeps the drone afloat if it has to land on water |
| **HydroSupport (AquaGuard Frame)** | 12-rod support frame (8 attached to the drone body, 4 to the boat structure) for structural support and water safety |
| **CamGuard** | Retractable camera: stowed at take-off and landing, extended in flight |
| **360° camera** | Full aerial view for mapping, inspection and surveillance |
| **Return-to-Home (RTL)** | Safety return if something goes wrong |
| **Waterproof design** | Built for wet conditions and remote ponds (not for heavy storms) |

**On-board sensors:** GNSS / NavIC / GPS receiver, IMU (accelerometer and gyroscope), magnetometer, airspeed (pitot) sensor, temperature / humidity / environmental sensors, and vibration and battery health monitoring. Control is by digital / remote controller.

## Benefits to farmers

Saves time, reduces cost, increases yield and improves safety.

## Repository layout

```
.
├── README.md
├── docs/
│   └── Fish_Feeding_Drone_Presentation-SPYNMOS.pptx   # concept presentation
├── models/
│   └── drone/
│       └── SPYNMOS_DRONE_FISH_FEEDING.blend           # main drone model (Blender 4.5)
└── assets/
    ├── fish3d/                                        # fish model: .obj .fbx .dae .3ds + texture
    └── waterfall/
        └── waterfall.blend                            # waterfall scene (Blender 2.79)
```

## Opening the models

- **Drone model:** open `models/drone/SPYNMOS_DRONE_FISH_FEEDING.blend` in Blender 4.5 or newer.
- **Waterfall scene:** saved in Blender 2.79. Newer versions of Blender can open it, but materials may need rework.
- **Fish model:** import the `.obj`, `.fbx`, `.dae` or `.3ds` file into any 3D tool. The texture is in `assets/fish3d/Texture/`.

## Status

Concept stage. The 3D models and the presentation exist. There is no flight firmware or hardware build in this repository yet, and the AI-generated image in the presentation is for reference only.
