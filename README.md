# BME5014 – Deep Learning for Biomedical Engineers

Course materials, recitation notebooks, and assignments for **BME5014**, built around examples and exercises relevant to biomedical engineering (vitals monitoring, dosage calculations, medical imaging, physiological signals).

## Structure

Materials are organized by semester:

```
F26/                        <- Fall 2026
└── recitation_0/
    ├── Rec-0.1_Python_Fundamentals_BME5014.ipynb
    ├── Rec-0.1_Python_QuickCheck_BME5014.ipynb
    ├── Rec-0.2_OOP_Fundamentals_BME5014.ipynb
    ├── Rec-0.2_OOP_QuickCheck_BME5014.ipynb
    ├── Rec-0.3_NumPy_Fundamentals_BME5014.ipynb
    └── Rec-0.3_NumPy_QuickCheck_BME5014.ipynb
```

Each notebook has an **Open in Colab** badge at the top — click it to open and run the notebook directly in Google Colab, no local setup required.

## Recitation 0.1: Python Fundamentals

An introduction/refresher on Python fundamentals (variables, control flow, functions, classes, NumPy) using biomedical examples (vitals monitoring, dosage calculations, small medical-image patches) instead of generic ones, to connect directly with the modeling work later in the course (CNNs on medical images, signal processing on physiological data, etc.).

- **Fundamentals** notebook: walkthrough + explanations, run every cell yourself.
- **Quick Check** notebook: auto-graded practice exercises (`assert`-based) to self-test the same concepts.

## Recitation 0.2: Object-Oriented Programming (OOP)

Classes, objects, inheritance, polymorphism, and dunder methods, explained with biomedical examples (infusion pumps, biosignal recordings, signal arithmetic). The final section shows why this matters for deep learning: PyTorch models (`nn.Module`) and datasets (`Dataset`, `DataLoader`) are ordinary Python classes built on exactly these concepts.

- **Fundamentals** notebook: step-by-step walkthrough, from the basics to a runnable PyTorch model and ECG `Dataset`.
- **Quick Check** notebook: eight auto-graded exercises (`assert`-based) covering classes, encapsulation, inheritance, polymorphism, dunder methods, class attributes, the `Dataset` pattern, and callable objects.

## Recitation 0.3: NumPy Fundamentals

Arrays, shapes, data types, indexing and slicing (views vs copies), boolean masking, `np.where`, axis-based aggregations, broadcasting, reshaping, and the different kinds of products, using biomedical data (ECG-like signals, grayscale image patches, vital signs, multichannel recordings). Includes a MATLAB-to-NumPy cheat sheet and a closing example that preprocesses a noisy multichannel recording.

- **Fundamentals** notebook: walkthrough with short "Your turn" prompts. Everything here carries over almost unchanged to PyTorch tensors.
- **Quick Check** notebook: twelve auto-graded exercises (`assert`-based), from creating arrays to a small signal-preprocessing challenge.
