# Web_Scrapping_AIML

#PROBLEM 1

# IMDb Filmography Web Scraping

This is a Python web scraping script that allows you to retrieve the filmography of any actor from IMDb in descending order. Simply provide the name of the actor as input, and the script will fetch and display the films done by the actor.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python packages: `requests` and `beautifulsoup4`

You can install the required Python packages using `pip`:

```bash
pip install requests beautifulsoup4
```

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/imdb-filmography-web-scraper.git
cd imdb-filmography-web-scraper
```

2. Make sure you have Python 3.x installed on your system. If not, you can download it from the official website: https://www.python.org/downloads/

3. Install the required Python packages:

```bash
pip install requests beautifulsoup4
```

## How to Use

1. Open a terminal or command prompt and navigate to the folder containing the script.

2. Run the script using the following command:

```bash
python filmography_scraper.py
```

3. You will be prompted to enter the name of the actor whose filmography you want to retrieve. For example, you can enter "Leonardo DiCaprio" or any other actor's name.

4. The script will fetch the filmography and display the films done by the actor in descending order, along with their release years.

## Example

```bash
$ python filmography_scraper.py
Enter the name of the actor: Leonardo DiCaprio

Films done by Leonardo DiCaprio in descending order:
1. Killers of the Flower Moon-2023
2. Don't Look Up-2021
3. Once Upon a Time... In Hollywood-2019
4. Lil Dicky: Earth-2019
5. The Revenant-2015
6. The Audition-2015
7. The Wolf of Wall Street-2013
8. The Great Gatsby-2013
9. Titanic: Deleted Scenes-2012
10. Django Unchained-2012
11. J. Edgar-2011
12. Inception: The Cobol Job-2010
13. Inception-2010
14. Shutter Island-2010
15. Revolutionary Road-2008
```

## Note

- The script uses web scraping to fetch data from IMDb. As IMDb's website structure may change over time, the script may need updates in the future to work with any structural changes.

- Use this script responsibly and respect IMDb's terms of service. Avoid making too many requests in a short period to prevent overloading their servers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Make sure to replace `your-username` in the clone URL with your actual GitHub username before using it in your repository. The provided content covers the project overview, installation steps, usage instructions, example, and important notes for the new users. Additionally, it includes a license section, assuming you are using the MIT License for the project. You can modify the license information according to your preference.


