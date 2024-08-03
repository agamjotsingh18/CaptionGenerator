# CaptionGenerator

The **Caption Generator** project is a web application that allows users to generate captions for their uploaded photos or image links. The project incorporates a login system to authenticate users and uses the Chat GPT API to generate three different captions for each uploaded photograph.

## Features 

- User Authentication: Users can sign up and log in to access the caption generation features. 
- Image Upload: Upload images or provide image URLs for caption generation. 
- Caption Generation: Generate three distinct captions for each image using the Chat GPT API. 
- Caption Display: View generated captions and select your preferred one. 
- User Profile: Manage user profiles and view previously uploaded images and generated captions. 
  
## Installation 
1. Clone the repository: 
 
 ```
git clone https://github.com/agamjotsingh18/CaptionGenerator.git
```
2. Navigate to the project directory: 
 ```
cd CaptionGenerator
```
3. Install dependencies: 
 ```
npm install
```
4. Set up environment variables: 
 
Create a `.env` file in the root directory of the project and add the following environment variables: 
 
 ```
PORT=5000 
MONGO_URI=<Your MongoDB Connection String> 
JWT_SECRET=<Your JWT Secret> 
CHAT_GPT_API_KEY=<Your Chat GPT API Key>
```
5. Run the application: 
```
npm start
```
The application will be available at `http://localhost:5000`. 
 
## Usage 
1. Sign Up / Log In: Use the authentication system to sign up or log in. 
2. Upload Image: Upload an image or provide an image URL. 
3. Generate Captions: Click the button to generate captions for the uploaded image. 
4. View Captions: Review the three generated captions and choose the one you like best. 
5. Profile Management: Access your profile to manage your details and view your uploaded images and captions. 

## Technologies Used 
- Frontend: React.js, CSS 
- Backend: Node.js, Express.js 
- Database: MongoDB 
- Authentication: JWT (JSON Web Tokens) 
- API: Chat GPT API
  
## Contributing 
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure that your code follows the project's coding standards and includes appropriate tests. 
 
1. Fork the repository. 
 
2. Create a new branch: 
 ```
git checkout -b feature/YourFeature 
```
3. Make your changes. 
 
4. Commit your changes: 
 ```
git commit -am 'Add feature: YourFeature' 
```

5. Push to the branch: 
 ```
git push origin feature/YourFeature 
```

6. Submit a pull request.
