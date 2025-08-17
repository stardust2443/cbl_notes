# Dissecting size_function.cpp

## Purpose
size function is a cosmological term for a function that tells you how many voids you should expect to find per unit volume for a given range of sizes (radii). The cosmological model we've used as an example here is the planck18 LCDM model with radius (R = 1 Mpc/h) and redshift (z = 1).

## Required Data/Inputs
We did not use any external datasets/ files. We have input the Planck18 model and used parameters like R = 1 Mpc/h, redshift = 1, SVdW theoretical model ( -0.7 density constant) and b_eff = 1.

## Libraries & Headers
LCDM header is the c++ embodiment of the standard model of cosmology. And, LCDM object holds all the fundamental cosmological parameters useful for all the calculations.

SizeFunction class contains the specific mathematical machinery to calculate the abundance of cosmic voids. It requires a Cosmology object (LCDM object here) during its creation to know the physical rules and parameters of the universe it's supposed to be working in.

## Step-by-Step Code Analysis

### 1. Setup and namespace

### 2. Load data

### 3. Compute size function

### 4. Output results

## Possible Modifications

## Python reimplementation plan

## Julia reimplementation plan
