<!DOCTYPE html>
<html>
<head>
  <title>AI Paryaj Login</title>
</head>
<body>

<h2>Login AI Paryaj</h2>

<input type="email" id="email" placeholder="Email"><br><br>
<input type="password" id="password" placeholder="Password"><br><br>

<button onclick="login()">Login</button>
<button onclick="googleLogin()">Login with Google</button>

<script type="module">
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
import { getAuth, signInWithEmailAndPassword, GoogleAuthProvider, signInWithPopup } 
from "https://www.gstatic.com/firebasejs/10.7.1/firebase-auth.js";

const firebaseConfig = {
  apiKey: "AIzaSyCij77S8z7V-UtUoTNoFadMy0OJDyYsC6c",
  authDomain: "ai-paryaj-e41c4.firebaseapp.com",
  projectId: "ai-paryaj-e41c4",
  storageBucket: "ai-paryaj-e41c4.firebasestorage.app",
  messagingSenderId: "228447385209",
  appId: "1:228447385209:web:4dc86306dcf12f8e16c6a8"
};

const app = initializeApp(firebaseConfig);
const auth = getAuth(app);

// LOGIN EMAIL
window.login =#parye-la-
parye la san limit
