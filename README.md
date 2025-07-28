#  Car Rental Platform

A full-stack web application designed to provide a seamless car rental experience for users, complemented by a powerful administrative dashboard for managing the vehicle inventory and bookings.

---

##  Features

###  User Features

* **User Authentication**: Secure sign-up and login system for users.
* **Browse & Search**: Easily browse a wide selection of available cars.
* **Search & Filter**: Find the perfect car by searching for make, model, or features.
* **Booking System**: Simple and intuitive process to book a car for specific dates.
* **My Bookings**: A dedicated page for users to view and manage their rental history and upcoming bookings.
* **Responsive UI**: Clean, modern, and fully responsive design that works on all devices.

### Admin Features

* **Admin Dashboard**: A central hub to monitor key statistics like total cars, bookings (pending/confirmed), and revenue.
* **Car Management**:
    * **Add New Cars**: Easily add new vehicles to the platform with details like brand, model, year, price, category, transmission, fuel type, seating capacity, and location.
    * **Manage Cars**: View all listed cars, update their details, or remove them from the platform.
* **Booking Management**: Track all customer bookings, approve or cancel requests, and manage booking statuses.

---

## 🛠️ Tech Stack

* **Frontend**: [e.g., React.js, Vite, Next.js]
* **Backend**: [e.g., Node.js, Express.js]
* **Database**: MongoDB
* **Styling**: [e.g., Tailwind CSS, Material-UI, CSS Modules]
* **Authentication**: [e.g., JWT (JSON Web Tokens)]

---

## Screenshot
<img width="1470" height="956" alt="Screenshot 2025-07-21 at 8 57 46 PM" src="https://github.com/user-attachments/assets/5b824679-f6f6<img width="1470" height="956" alt="Screenshot 2025-07-21 at 8 58 51 PM" src="https://github.com/user-attachments/assets/89b1423b-5573-4547-bf73-0c767f8caf13" />
-4420-ad0f-bb153c029c8c" />

<img width="1470" height="956" alt="Screenshot 2025-07-21 at 8 59 06 PM" src="https://github.com/user-attachments/assets/13725683-6ee1-46c3-9a86-5c83234bbd28" />
<img width="1470" height="956" alt="Screenshot 2025-07-21 at 8 59 17 PM" src="https://github.com/user-attachments/assets/7aa02dac-979b-45dc-9d4f-1fc318aaefae" />
<img width="1470" height="956" alt="Screenshot 2025-07-21 at 8 59 55 PM" src="https://github.com/user-attachments/assets/ebe50da0-fbeb-40a6-ba99-7729a9943ed5" />





## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have the following software installed on your system:

* [Node.js](https://nodejs.org/) (which includes npm)
* [Git](https://git-scm.com/)
* [MongoDB](https://www.mongodb.com/try/download/community) (Make sure the MongoDB server is running)

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-repo-name
    ```
3.  **Install Backend Dependencies:**
    ```sh
    cd backend
    npm install
    ```
4.  **Install Frontend Dependencies:**
    ```sh
    cd ../frontend
    npm install
    ```

### Configuration

The backend requires a `.env` file for environment variables.

1.  Navigate to the `backend` directory.
2.  Create a file named `.env`.
3.  Add the following variables. Replace the placeholder values with your actual configuration details.
    ```env
    MONGO_URI=mongodb://localhost:27017/carrental
    JWT_SECRET=your_super_secret_jwt_key
    PORT=5000
    ```

### Running the Application

1.  **Start the Backend Server:**
    From the `backend` directory, run:
    ```sh
    npm start
    ```
    The backend server will start on `http://localhost:5000` (or the port you specified).

2.  **Start the Frontend Development Server:**
    Open a new terminal, and from the `frontend` directory, run:
    ```sh
    npm start
    ```
    The frontend application will open in your browser at `http://localhost:3000`.

---

## Usage

### As a User

1.  Register for a new account or log in with existing credentials.
2.  On the homepage, select your desired pickup location and dates.
3.  Browse the list of available cars.
4.  Click on a car to view more details.
5.  Proceed to book the car for your selected dates.
6.  You can view your active and past bookings on the "My Bookings" page.

### As an Admin

1.  Log in using an admin account.
2.  You will be redirected to the Admin Dashboard.
3.  Use the sidebar to navigate between:
    * **Dashboard**: View analytics and recent activities.
    * **Add car**: Fill out the form to add a new vehicle to the inventory.
    * **Manage Cars**: View, edit, or delete existing car listings.
    * **Manage Bookings**: Review new booking requests and update their status (e.g., approve, cancel).

---

##  Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/your-repo-name/issues).

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file for details.
