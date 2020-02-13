# Rust

Projet par Bastien NISOLE et Alexis DESJARDINS étudiants en 4AL1

Ce projet permet de traiter une image PPM (P3) (**test.ppm**) qui sera nommée **output.ppm**
Il utilise une version modifiée de ppma_io afin de traiter l'image.

## Commandes pour compiler le Rust

cargo +nightly build

## Commandes pour lancer les benchmark Rust

```bash
cargo +nightly bench
```

## Commandes pour lancer les tests Rust

```bash
cargo +nightly test
```

## Création de la documentation

Un dossier target est créé. Il faut aller dans le dossier `target/doc/ppm` et ouvrir le fichier `index.html` sur votre navigateur favori

```bash
cargo +nightly doc --no-deps
```

## Commandes pour lancer le python (v2.7)

```bash
python runner.py
```

| args | description |
| ----------- | ----------- |
| *none* | apply gray by default |
| gray | turn the ppm file to gray |
| reverted | invert the ppm file |
