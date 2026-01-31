<!-- Improved compatibility of back to top link -->
<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/delmsyap/code-server-copilot">
    <img
      src="images/copilot.png"
      alt="Logo"
      width="100%"
      style="max-width: 320px;"
    />
  </a>

</div>
<h3 align="center">code-server-copilot</h3>

  <p align="center">
    Enable GitHub Copilot support in <a href="https://github.com/coder/code-server">code-server</a> (VS Code in the browser).
    <br />
    <br />
    <a href="https://github.com/delmsyap/code-server-copilot/issues">Report Bug</a>
    ·
    <a href="https://github.com/delmsyap/code-server-copilot/issues">Request Feature</a>
  </p>
</div>

---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>

---

## About The Project

**code-server-copilot** provides a straightforward way to use **GitHub Copilot** inside **code-server**, bringing AI-assisted coding to browser-based VS Code environments.

This is useful for:
- Remote development servers
- Self-hosted VS Code instances
- Low-resource or mobile-first setups

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Getting Started

Follow the steps below to enable Copilot in your code-server setup.

### Prerequisites

- A working **code-server** installation
- An active **GitHub Copilot** subscription
- GitHub account authenticated in VS Code / code-server

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/delmsyap/code-server-copilot.git
   ```
2. ```sh
   bash install-copilot.sh
   
    GitHub Copilot Extensions Installer
    ====================================
    
    Detected VS Code version: 1.108.1
    
    Processing GitHub.copilot...
      Found compatible version: 1.388.0
    Installing GitHub.copilot v1.388.0...
      Downloading...
      % Total    % Received % Xferd  Average Speed   Time
    ```
3. Restart code-server after installation.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---


### Usage
Once installed:
- Open code-server in your browser
- Sign in to GitHub if prompted
- Verify that GitHub Copilot is enabled in the Extensions panel
- Start coding — Copilot suggestions should appear automatically

<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

