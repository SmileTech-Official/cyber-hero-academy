<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cyber-Hero Academy | Register</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; color: #333; line-height: 1.6; }
        header { background: #1a237e; color: white; padding: 60px 20px; text-align: center; }
        .container { max-width: 800px; margin: auto; padding: 20px; }
        h1 { font-size: 2.5rem; margin-bottom: 10px; }
        
        /* Form Styling */
        .registration-box { background: #f4f4f9; padding: 30px; border-radius: 15px; border-top: 5px solid #ffca28; margin-top: 40px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        .form-group { margin-bottom: 15px; }
        label { display: block; margin-bottom: 5px; font-weight: bold; }
        input, select { width: 100%; padding: 10px; border: 1px solid #ccc; border-radius: 5px; box-sizing: border-box; }
        
        .submit-btn { background: #1a237e; color: white; padding: 15px; border: none; width: 100%; border-radius: 5px; font-size: 1.1rem; cursor: pointer; transition: 0.3s; }
        .submit-btn:hover { background: #3949ab; }
        
        footer { text-align: center; padding: 20px; font-size: 0.8rem; color: #777; }
    </style>
</head>
<body>

<header>
    <h1>Cyber-Hero Academy</h1>
    <p>Secure their future. Start with a secret code.</p>
</header>

<div class="container">
    <div id="register" class="registration-box">
        <h2 style="text-align: center;">Register Your Child</h2>
        <form action="https://formspree.io/f/your-id-here" method="POST">
            <div class="form-group">
                <label>Parent/Guardian Name</label>
                <input type="text" name="parent_name" placeholder="Enter your full name" required>
            </div>
            
            <div class="form-group">
                <label>Email Address</label>
                <input type="email" name="email" placeholder="email@example.com" required>
            </div>

            <div class="form-group">
                <label>Child's Age</label>
                <select name="age" required>
                    <option value="">Select Age</option>
                    <option value="8-10">8-10 years old</option>
                    <option value="11-13">11-13 years old</option>
                </select>
            </div>

            <div class="form-group">
                <label>Preferred Workshop</label>
                <select name="workshop_type" required>
                    <option value="online">Online Webinar</option>
                    <option value="in-person">In-Person Camp</option>
                </select>
            </div>

            <button type="submit" class="submit-btn">Reserve a Spot</button>
        </form>
    </div>
</div>

<footer>
    &copy; 2026 Cyber-Hero Academy | Designed by a Future Security Expert
</footer>

</body>
</html>
