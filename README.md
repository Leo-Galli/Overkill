# Overkill

[![Language](https://img.shields.io/badge/language-python-blue.svg?style=flat)](https://www.python.org)  
[![Module](https://img.shields.io/badge/module-pygame-brightgreen.svg?style=flat)](http://www.pygame.org/news.html)  
[![License](https://img.shields.io/github/license/Leo-Galli/Overkill)](https://github.com/Leo-Galli/Overkill/blob/main/LICENSE)  

## SonarCloud Metrics

[![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=coverage)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=bugs)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Duplicated Lines](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=Leo-Galli_Overkill&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)  
[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-light.svg)](https://sonarcloud.io/summary/new_code?id=Leo-Galli_Overkill)

---

## About Overkill

Overkill is a fast-paced 2D side-scrolling shooter developed in Python using the Pygame library. Players control a lone hero who runs across the battlefield, dodging enemy fire and eliminating threats in a retro arcade-style environment. The game blends classic shooter mechanics with modern enhancements for an engaging experience.

---

## Features

- Horizontal run-and-gun gameplay
- Pixel-style graphics with custom assets
- Sound effects and background music
- AI-driven enemy behavior
- Keyboard controls for movement and shooting
- Lightweight and portable — no installation required

---

## How to Play

### Option 1: Run the Executable

If Python and Pygame are not installed:
- Double-click the `.exe` file to launch the game.
- Important: The `.exe` must remain in the same directory as the `sounds`, `images`, and `fonts` folders.

### Option 2: Run from Source

1. Install dependencies:
   ```bash
   pip install pygame
   ```

2. Launch the game:
   ```bash
   cd Overkill
   python main.py
   ```

---

## Development and Testing

This project uses Pytest for unit testing and Flake8 for linting. Continuous integration is managed via GitHub Actions.

To run tests locally:
```bash
pytest
```

To lint your code:
```bash
flake8 .
```

---

## Project Structure

```
Overkill/
├── assets/
│   ├── images/
│   ├── sounds/
│   └── fonts/
├── main.py
├── requirements.txt
├── test_main.py
└── .github/
    └── workflows/
        └── python-app.yml
```

---

## Contributing

Contributions are welcome. To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to your branch (`git push origin feature/my-feature`)
5. Open a pull request

---

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Leo-Galli/Overkill/blob/main/LICENSE) file for details.

---

## Acknowledgments

- [Pygame](https://www.pygame.org/) for the game engine
- [SonarCloud](https://sonarcloud.io/) for code quality analysis
- [GitHub Actions](https://github.com/features/actions) for CI/CD automation

---
