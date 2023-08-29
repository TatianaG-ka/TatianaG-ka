![header_Tetiana_Golinska](https://github.com/TatianaG-ka/TatianaG-ka/assets/52859818/53893ade-387e-43b7-8b34-2b4d37db0e5d)

### ![about Tetiana Golinska](https://github.com/TatianaG-ka/TatianaG-ka/assets/52859818/a97c0a91-e752-4bde-a180-c029423ea8dc) About me


```javascript

let personal = Personal(name: "Tetiana Golinska",
                        mainTechStack: "Rest Assured and Selenium Webdriver with Java",
                        description: "I have 4 years of experience as a software tester,
                        4 of them as manual tester, including 1 year of experience in automation testing.
						I've always been interested in different areas, but for the last 2 years 
						I've been passionate most of all about automation testing. ")

var contact = Contact(email: "tatiana.golinska@gmail.com",
                      url: "https://www.linkedin.com/in/tetiana-golinska/ ",
                      location: "Warsaw, Poland"
                      )

let automationTester = AutomationTester(personal: personal, contact: contact)

struct AutomationTester {
    let personal: Personal;
    let contact: Contact
}

struct Personal {
    let name: String;
    let mainTechStack: String;
    let description: String
}

struct Contact {
    let email: String;
    let url: String;
    let location: String
}
```
