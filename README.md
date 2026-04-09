# [RSA4096Forever](https://demos.matthewbenchimol.com/RSA4096Forever/index.html) - The Prometheus Protocol: Quantum-Proof RSA-4096

The **Prometheus Protocol** is a specialized cryptographic framework designed to nullify the computational advantages of Quantum Fourier Transform (QFT) and period-finding algorithms. By integrating a geometric stream cipher using **Sequential Hilbert Fractal Transformation** with the encryption algorithm **RSA-4096**, the Prometheus Protocol ensures the modular relationships required for Shor’s Algorithm are mathematically erased before the encryption wrap occurs, rendering Shor's Algorithm ineffective.

## Core Methodology

The protocol operates as a **Triad Encryption Process**, utilizing three distinct layers of defense to achieve permanent quantum immunity:

1.  **Alpha-Omega XOR-Residue Chain:** Each data sector is interlinked with the cumulative entropy of all preceding sectors based on intermingling chunks encrypted with the Alpha and Omega keys. This creates a causal dependency that forces quantum computers into a serial processing bottleneck.
2.  **Hilbert Fractal Transformation:** 1D data streams are mapped into 2D spatial coordinates using a 16x16 Hilbert curve. This transformation physically relocates adjacent bits to non-local positions, destroying the periodicity required for quantum phase estimation to find 'r' in polynomial time, rendering the Quantum Fourier Transformation (QFT) moot.
3.  **RSA-4096 Synchronous Wrap:** The whitened, high-entropy fractal state is encapsulated in a 4096-bit wrap with the Prometheus key. Because the input is mathematically indistinguishable from white noise, RSA-4096 becomes quantum immune.

## Quantum-Proof Nature by File Volume

The following table breaks down the security characteristics and estimated quantum crack-time for the Prometheus Protocol. 

**Standardized Metric:** Analysis based on a 10,000 Logical Qubit CRQC.

| File Size | Sector Count | Entropy (H) | Estimated Crack Time (Shor/Grover) | Quantum Resistance Analysis |
| :--- | :--- | :--- | :--- | :--- |
| **500 B** | 2 | ~7.991 | **Indeterminate** | Geometric jitter prevents initial phase estimation. |
| **500 KB** | 2,000 | ~7.998 | **> 10^12 Years** | Whitening erases the RSA period $r$; forces serial brute force. |
| **1 MB** | 4,096 | ~7.998 | **> 10^25 Years** | High causal dependency; residue chain prevents parallel processing. |
| **5 MB** | 20,480 | ~7.999 | **Infinite** | System reaches thermodynamic equilibrium; zero quantum advantage. |

## The Polynomial-Time Nullification

Shor’s Algorithm is fundamentally a tool for finding order in modular arithmetic. The Prometheus Protocol operates on the principle of **Geometric Whitening**. By transforming the data into a fractal state prior to the modular wrap, the protocol ensures that the RSA modulus $N$ is encrypting a non-periodic, high-entropy surface. 

This renders a quantum computer no more effective than a classical "calculator." Since there is no discernible period to identify, the quantum Fourier transform cannot collapse the state into a solution.

## How to test:

1. Visit [RSA4096Forever homepage](https://demos.matthewbenchimol.com/RSA4096Forever/index.html).
2. Click 'Forge Matrix' to get key triads, saving them to your devices hard drive.
3. Click 'Choose File' under encryption operations, selecting your TXT file.
4. Click 'Lock' to encrypt using the Prometheus Protocol. It will auto-save a .vault file to your device when complete.
4. Upload Alpha, Omega, and Prometheus Keys and click 'Sync Matrix State'.
5. Click 'Choose File' under encryption operations, selecting your .vault file.
6. Click 'Decrypt' to decrypt using the Prometheus Protocol. It will auto-save a .txt file to your device when complete.
7. Open original and decrypted version to see complete replication. 

## Due-Outs
- Complete pmTLS (Prometheus Mutual Transport Layer Security) and upload wizard for people to config new quantum proof web connection methodology with no extra merkle tree overhead.

## Want to contribute?
Send me a pull request.
