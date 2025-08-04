

# Doc 24x7

Doc 24x7 is a comprehensive healthcare web application designed to streamline the process of connecting patients with medical professionals. The platform offers a seamless experience for users to learn about available healthcare services, view detailed doctor profiles, and book appointments online with instant feedback. With a modern, responsive interface powered by React and Vite, Doc 24x7 ensures accessibility and ease of use across devices.

The application features a dynamic navigation bar, animated transitions, and a visually appealing layout using Tailwind CSS and icon libraries. Patients can explore a range of medical specialties, check doctor availability, and submit appointment or contact forms securely. Real-time notifications and smooth user interactions make Doc 24x7 an ideal solution for clinics, hospitals, or healthcare providers looking to enhance their digital presence and improve patient engagement.

A modern healthcare web app built with React and Vite, featuring appointment booking, doctor profiles, contact form, and more. Styled with Tailwind CSS and enhanced with interactive UI components.

## Features

- **Responsive Navigation Bar** with smooth scrolling and animated transitions
- **About Section**: Highlights healthcare services, 24/7 support, and patient testimonials
- **Doctors Section**: Lists doctors with specialization, experience, and availability
- **Appointment Booking**: Secure online form with instant feedback (SweetAlert2)
- **Contact Form**: Send messages directly to the clinic, with success notifications
- **Modern UI**: Built with Tailwind CSS, Lucide icons, and FontAwesome
- **Animations**: GSAP-powered transitions for engaging user experience
- **24/7 Support**: Prominently displayed for user assurance

## Installation

1. **Clone the repository**
   ```powershell
   git clone https://github.com/Jagadeeshrayavelluri97/Doc-24x7
   cd "Doc 24x7"
   ```

2. **Install dependencies**
   ```powershell
   npm install
   ```

3. **Start the development server**
   ```powershell
   npm run dev
   ```

4. **Build for production**
   ```powershell
   npm run build
   ```

5. **Preview production build**
   ```powershell
   npm run preview
   ```

6. **Lint the code**
   ```powershell
   npm run lint
   ```

## Technologies Used

- **React 18**
- **Vite**
- **Tailwind CSS**
- **FontAwesome & Lucide Icons**
- **GSAP (Animations)**
- **SweetAlert2 (Notifications)**
- **Web3Forms (Form backend)**

## Folder Structure

```
src/
  components/
    About.jsx
    Appointment.jsx
    Contact.jsx
    Doctors.jsx
    NavBar.jsx
  App.jsx
  App.css
  index.css
  main.jsx
public/
  vite.svg
```

## Environment

No environment variables required for basic usage. Appointment and contact forms use [Web3Forms](https://web3forms.com/) for backend submission.

## License

MIT
