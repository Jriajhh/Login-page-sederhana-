* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

body::before {
    content: '';
    position: absolute;
    top: 0; left: 0; width: 100%; height: 100%;
    background: rgba(18, 18, 18, 0.5);
    z-index: -1;
}

.login-card {
    position: relative;
    width: 400px;
    padding: 40px;
    background: rgba(255, 255, 255, 0.1); 
    backdrop-filter: blur(15px); 
    border: 1px solid rgba(106, 0, 255, 0.2);
    border-radius: 20px;
    box-shadow: 0 25px 50px rgba(10, 10, 245, 0.3);
    overflow: hidden;
    transition: transform 0.3s ease;
}

.login-header h2 {
    color: #fff;
    font-weight: 600;
    text-align: center;
    margin-bottom: 5px;
}

.login-header p {
    color: #ccc;
    text-align: center;
    font-size: 0.9em;
    margin-bottom: 30px;
}
.input-group {
    position: relative;
    margin-bottom: 25px;
}

.input-group input {
    width: 100%;
    padding: 12px 20px;
    background: transparent;
    border: 2px solid rgba(255, 255, 255, 0.3);
    border-radius: 10px;
    color: #fff;
    font-size: 16px;
    outline: none;
    transition: 0.3s;
}

.input-group label {
    position: absolute;
    left: 20px;
    top: 50%;
    transform: translateY(-50%);
    color: #fff;
    pointer-events: none;
    transition: 0.3s;
    background: transparent; 
    padding: 0 5px;
}

.input-group input:focus,
.input-group input:valid {
    border-color: #00d2ff;
}

.input-group input:focus ~ label,
.input-group input:valid ~ label {
    top: 0;
    font-size: 12px;
    color: #00d2ff;
    background: #2a2a3e;
    border-radius: 5px;
}


.input-icon, .toggle-password {
    position: absolute;
    right: 15px;
    top: 50%;
    transform: translateY(-50%);
    color: #fff;
    font-size: 1.1em;
}

.toggle-password {
    cursor: pointer;
    transition: color 0.3s;
}

.toggle-password:hover {
    color: #00d2ff;
}


.form-actions {
    display: flex;
    justify-content: space-between;
    font-size: 0.85em;
    color: #fff;
    margin-bottom: 25px;
}

.form-actions a {
    color: #00d2ff;
    text-decoration: none;
}

.btn-login {
    width: 100%;
    padding: 12px;
    border: none;
    border-radius: 10px;
    background: linear-gradient(90deg, #00d2ff, #3a7bd5);
    color: #fff;
    font-size: 16px;
    font-weight: 600;
    cursor: pointer;
    transition: 0.3s;
    position: relative;
}

.btn-login:hover {
    transform: translateY(-2px);
    box-shadow: 0 5px 15px rgba(0, 210, 255, 0.4);
}

.loader {
    display: none;
    width: 20px;
    height: 20px;
    border: 3px solid #fff;
    border-top: 3px solid transparent;
    border-radius: 50%;
    animation: spin 1s linear infinite;
    margin: 0 auto;
}

@keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }

.login-footer {
    margin-top: 20px;
    text-align: center;
    font-size: 0.9em;
    color: #ccc;
}

.login-footer a {
    color: #00d2ff;
    font-weight: 600;
    text-decoration: none;
}

.shake {
    animation: shake 0.5s;
}

@keyframes shake {
    0% { transform: translateX(0); }
    25% { transform: translateX(-10px); }
    50% { transform: translateX(10px); }
    75% { transform: translateX(-10px); }
    100% { transform: translateX(0); }
}

@media (max-width: 450px) {
    .login-card {
        width: 90%;
        padding: 30px 20px;
    }
}
