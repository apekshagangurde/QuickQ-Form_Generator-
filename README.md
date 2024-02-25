# QuickQ

Welcome to QuickQ - Your Form Generator Website!

QuickQ simplifies form creation, data storage, and retrieval processes, making it easy for both beginners and experts. This project was initiated under the guidance of Pradnya Mam, where our team embarked on a journey from zero knowledge, not even knowing React, to building a fully functional form generator website.

## Introduction

QuickQ offers a user-friendly interface for creating professional-looking forms in minutes. Whether you're collecting feedback, conducting surveys, or gathering information, QuickQ streamlines the process, saving you time and effort.

## Technology Stack

### Frontend
- **React**: Powering the frontend development, React provides a modular and reusable UI components architecture, enhancing development efficiency and maintainability.

### Backend
- **Django Rest Framework (DRF)**: Leveraging Django Rest Framework for backend development, providing a robust foundation for building RESTful APIs swiftly and efficiently.

### Database
- **MongoDB**: Utilizing MongoDB as the database solution due to its flexible document-oriented structure, scalability, and ease of integration.

### API Testing
- **Postman**: Utilized for API testing, Postman offers a user-friendly interface for verifying endpoints, assessing response data, and ensuring the reliability and functionality of backend services.

### HTTP Client
- **Axios**: Employed for handling API requests, Axios simplifies the process of making asynchronous requests and handling responses, enhancing the efficiency of the application.

## Workflow

1. **Form Creation**: Users interact with the React UI to create forms.
2. **Data Storage**: Form responses are sent to MongoDB using Django's POST API.
3. **Data Retrieval**: Form data is retrieved from MongoDB and rendered on the React UI when users access the form.
4. **Form Submission**: Users' responses are stored in MongoDB via the POST API.
5. **View Responses**: The GET API retrieves stored responses from MongoDB and displays them on the React UI.
6. **Edit Forms**: Users can edit forms, and edited content is updated using the GET and PUT APIs, allowing seamless modification and storage of form data.
7. **Delete Forms**: Users have the option to delete forms. Upon deletion, the form data is removed from MongoDB, and the form is no longer accessible.
8. **Search Forms**: Users can search for specific forms using the search functionality. The search queries are processed, and relevant forms are retrieved and displayed on the React UI, providing users with a convenient way to find the forms they need.

## Use Case of QuickQ


![use case](https://github.com/apekshagangurde/QuickQ-form_generator-/blob/master/image/use%20case%20main.jpg)

## Demo Video

[Link to Video](https://raw.githubusercontent.com/apekshagangurde/QuickQ-form_generator-/master/image/form%20generator%20demo.mp4)



## Technical Use Case Diagram

![technical workflow](https://github.com/apekshagangurde/QuickQ-form_generator-/assets/100061307/5f521aa4-18d4-49c2-b4b5-340a3ed71464)


## Conclusion

QuickQ serves as a practical tool for form creation and data management, representing a valuable learning experience for our team. Through this project, we've enhanced our skills in frontend and backend development, API testing, database management, and collaboration.

Thank you for your attention. We're eager to answer any questions you may have.

---

This README was authored by [Apeksha Gangurde]  for QuickQ.
