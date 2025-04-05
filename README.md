# Vital Care Physiotherapy

Vital Care Physiotherapy is a web-based application designed to streamline the process of creating and printing patient prescriptions. The application provides a user-friendly interface for entering patient details, generating a preview of the prescription, and printing or downloading it as a PDF. The design ensures that the output matches the exact specifications of a professional prescription format.

## Features

### 1. **Patient Information Form**
- Collects essential details such as:
  - Patient's Name
  - Gender
  - Age
  - Date
  - Chief Complaints
  - Diagnosis
  - Treatment Plan
  - Supplements
  - Additional Advice
- Pre-filled placeholders guide users on how to input data.

### 2. **Dynamic Preview**
- Generates a real-time preview of the prescription based on the entered data.
- Ensures the preview matches the exact design of a professional prescription.

### 3. **Print and Download Options**
- Allows users to:
  - Print the prescription directly.
  - Download the prescription as a PDF by selecting "Save as PDF" in the print dialog.

### 4. **Responsive Design**
- Optimized for various screen sizes:
  - Desktop
  - Tablet
  - Mobile
- Ensures a seamless user experience across devices.

### 5. **Professional Prescription Layout**
- Includes:
  - Clinic logo and details.
  - Doctor's name, qualifications, and contact information.
  - Facilities offered by the clinic.
  - Patient details and prescription content.
  - Footer with a disclaimer: "NOT FOR MEDICO LEGAL PURPOSE."

### 6. **Customizable Styles**
- Inline styles and media queries ensure the prescription layout adapts to different screen sizes and print formats.
- Print-specific styles ensure the output is optimized for A4 paper.

## Project Structure
.vitalcare-physiotherapy/ ├── .hintrc # Configuration for linting rules ├── index.html # Main HTML file containing the application ├── image.png # Logo for TATA 1mg (used in the prescription) ├── image2.png # Clinic logo (used in the prescription)


## How to Use

1. Open the `index.html` file in a browser.
2. Fill out the patient information form on the first step.
3. Click the "Next - Preview" button to generate a preview of the prescription.
4. Review the preview:
   - If changes are needed, click "Back to Form" to edit the details.
   - If satisfied, click "Print" to print the prescription or "Download as PDF" to save it.
5. For mobile users, the layout adjusts automatically for better usability.

## Technologies Used

- **HTML5**: For structuring the application.
- **CSS3**: For styling and responsive design.
- **JavaScript**: For dynamic content generation and interactivity.

## Responsive Design

The application is fully responsive and adapts to different screen sizes:
- **Desktop**: Full-width layout with all features visible.
- **Tablet**: Adjusted padding and font sizes for readability.
- **Mobile**: Stacked layout with simplified navigation.

## Print Optimization

- The prescription is formatted for A4 paper size.
- Print-specific styles ensure the output matches professional standards.
- Buttons and unnecessary elements are hidden during printing.

## Future Enhancements

- **Backend Integration**: Save patient data to a database for future reference.
- **Export Options**: Add support for exporting prescriptions in formats like Word or Excel.
- **Multi-language Support**: Allow users to generate prescriptions in different languages.
- **Authentication**: Add user login for secure access to patient data.

## License

This project is open-source and available under the [MIT License](LICENSE).

---
