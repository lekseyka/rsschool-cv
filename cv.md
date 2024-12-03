# Aleksey Krivitskiy
## Frontend Developer | React

## Contact me
* Gmail: aleksey.krivitskiy2020@gmail.com
* Telegram: https://t.me/aaleshaa

## About me

I'm a Frontend Developer with experience working with different technologies.
I want to study the basics in more depth and gain practical experience in solving various tasks.

## Skills

* ReactJs, Javascript, SCSS, Git.

## My code

```
 useEffect(() => {
        const fetchData = async () => {
            try {
                const response = await axios.post(
                    'https://suggestions.dadata.ru/suggestions/api/4_1/rs/suggest/address',
                    { query: address },
                    {
                        headers: {
                            'Content-Type': 'application/json',
                            'Authorization': 'Token YOUR_TOKEN'
                        }
                    }
                ).then(response => {
                    if(response.data.suggestions.length > 0) {
                        setSuggestions(response.data.suggestions);
                    }
                });
            } catch (error) {
                console.error('Ошибка при получении подсказок:', error);
            }
        }

        if (address !== '') {
            fetchData();
        } else {
            setSuggestions([]);
        }
    }, [address])
```

## Experience

Website Development:

* Creating and optimizing user interfaces.
* Integrating Telegram API into the website structure.

CRM System Enhancement:

* Developing functionality for data input and filtering.
* Interacting with the database.

CRM Development:

* Designing and developing user and administrative panels for CRM systems.
* Creating components and integrating them with the backend part of the system.
* Optimizing performance and improving UX/UI for user convenience.

Browser Process Automation Plugin Development:

* Writing a plugin on the ZennoPoster platform to simulate user behavior in the browser.
* Developing custom scenarios and integrating them with external services and APIs.
* Testing and debugging the written scripts.

Website Development on WordPress:

* Creation and setup of a website on the WordPress platform.
* Development of themes and plugins tailored to the client's specific needs.

Frontend Development on Magento 1/2:

* Development and support of e-commerce functionality on the Magento platform.
* Ensuring cross-browser compatibility and responsive design.

## Education

Graduated from the Belarusian National Technological University.

## English level

I have a B1 level certificate after studying at an English language school named "International House".
