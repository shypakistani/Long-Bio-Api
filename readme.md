# Long-Bio-Api

A Python-based API designed for generating and handling long biographies, configured for seamless deployment on Vercel. 

## Features
* **Protocol Buffers:** Utilizes Protobuf (`my_pb2.py`, `output_pb2.py`) for efficient, structured, and fast data serialization.
* **Serverless Deployment:** Fully configured via `vercel.json` for lightweight hosting on Vercel.
* **Pure Python:** Built entirely using Python 3 backend logic.

## Project Structure
* `index.py` - Main entry point and API route handling.
* `my_pb2.py` / `output_pb2.py` - Compiled Protocol Buffer definitions for data structures.
* `requirements.txt` - Python package dependencies.
* `vercel.json` - Deployment configurations for the Vercel platform.

## Getting Started

### Prerequisites
* Python 3.9+
* Vercel CLI (optional, for local development and hosting)

### Installation & Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/shypakistani/Long-Bio-Api/
   cd Long-Bio-Api
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the development server locally using Vercel CLI:
   ```bash
   vercel dev
   ```

## Deployment
Deploy live to Vercel with a single command:
```bash
vercel
```
