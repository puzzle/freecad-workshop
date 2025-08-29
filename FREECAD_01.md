# FreeCAD workshop

![alt text](freecad_logo.png)

## Khôi Tran 05.09.2025

---

## Presentation

https://puzzle.github.io/freecad-workshop

## Code

https://github.com/puzzle/freecad-workshop

## PDF

https://puzzle.github.io/freecad-workshop/PRESENTATION.pdf

## Markdown

https://puzzle.github.io/freecad-workshop/PRESENTATION.md

---

## Agenda

1. What is FreeCAD?
2. Compared to other 3D design applications
3. What is parametric CAD?
4. Simple FreeCAD workflow
5. Basic designs with FreeCAD: Sketches and operators
7. FreeCAD Installation & Hands-On: Design a simple cube

---

# What is FreeCAD

---

## What is CAD?

Computer-Assisted Design

🔑 Key Aspects of CAD:

- Parametric modeling: Define shapes with dimensions and constraints that can be updated later.
- 2D & 3D design: Supports both technical drawings (2D) and detailed 3D models.
- Accuracy: CAD models are mathematically precise, unlike hand sketches or artistic models.
- Documentation: CAD can generate technical drawings, assembly instructions, or manufacturing files.

---

## The dad-joke analogy

CAD: Excel for 3D-shapes

Blender: Painting or Sculpting with clay

Photoshop: Painting on canvas

---

## FEM - Finite Element Method

Simulate physical behavour of parts and structure under loads, heat, vibrations.

**FreeCAD has support for FEM.**

---

## CAM - Compuer-Aided Manufacturing

Generate machine instructions for manufacturing (CNC machines, G-code)

While FreeCAD has support, it is still recommended to use slicer software for 3D-printing.

---

## 🔍 Comparison: FreeCAD vs Similar Applications

| Feature / Tool          | **FreeCAD**                                              | **Fusion 360**                                       | **SolidWorks**                          | **Onshape**                           | **Blender** (3D Creation, not CAD-focused) |
| ----------------------- | -------------------------------------------------------- | ---------------------------------------------------- | --------------------------------------- | ------------------------------------- | ------------------------------------------ |
| **License / Cost**      | Free, Open Source (LGPL)                                 | Free hobbyist license, paid subscription for pro use | Paid (expensive, commercial)            | Subscription-based (cloud SaaS)       | Free (open source)                         |
| **Platform**            | Windows, macOS, Linux                                    | Windows, macOS (cloud-connected)                     | Windows only (VM workaround for Mac)    | Browser-based (any OS)                | Windows, macOS, Linux                      |
| **Parametric Modeling** | ✔️ Fully parametric                                      | ✔️ Fully parametric                                  | ✔️ Fully parametric                     | ✔️ Fully parametric                   | ❌ Not parametric (mesh-based)              |
| **Assembly Tools**      | Basic (Assembly workbenches, community add-ons)          | ✔️ Integrated assemblies                             | ✔️ Advanced assemblies                  | ✔️ Built-in assemblies                | ❌ No assembly workflow                     |
| **Ease of Learning**    | Moderate (engineer-oriented UI)                          | Beginner-friendly                                    | Moderate, steep curve for advanced      | Easy (intuitive, cloud-based)         | Steep curve, artist-focused                |
| **Community & Support** | Strong, open-source community                            | Large, official + community                          | Large professional support              | Growing community                     | Very large open-source community           |

---
