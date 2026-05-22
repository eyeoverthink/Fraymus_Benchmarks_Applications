# Fraymus Benchmarks & Applications

Benchmarking tools and standalone applications.

## Applications

- **BenchmarkRunner** - Benchmark Runner - Performance Testing
- **FraymusApp** - Fraymus App - Main Application
- **FraymusConvergence** - Fraymus Convergence - Neuro-Symbolic CLI
- **FraymusPrime** - Fraymus Prime - Interactive Console
- **FraymusConsole** - Fraymus Console - Command Deck
- **FraymusTest** - Fraymus Test - Testing Framework

## Dependencies

- LWJGL 3.3.3 (OpenGL, GLFW, STB)
- ImGui Java 1.86.11
- JOML 1.10.5
- Benchmark libraries

## Build

```bash
cd Asset-Manager
./gradlew build
```

## Run Benchmarks & Applications

```bash
./gradlew runBenchmark        # Run Benchmark Runner
./gradlew run                 # Run Fraymus App
./gradlew runConvergence      # Run Fraymus Convergence
./gradlew runPrime            # Run Fraymus Prime
./gradlew runConsole          # Run Fraymus Console
./gradlew runTest             # Run Fraymus Test
```

## Requirements

- Java 21
- Gradle 9.2+
