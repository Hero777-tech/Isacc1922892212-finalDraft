/* registration *//* registration *//* registration *//* registration *//* registration *//* registration */
/* registration *//* registration *//* registration *//* registration *//* registration *//* registration */
/* registration *//* registration *//* registration *//* registration *//* registration *//* registration */



/* Registration Fees Section */
.registration-section {
    padding: 60px 20px;
    background: #1e2a38;
    color: #ffffff;
}

.registration-heading,
.registration-process-heading {
    text-align: center;
    margin-bottom: 40px;
    font-size: 36px;
    color: #ff9800;
    font-family: 'Roboto', sans-serif;
}

.registration-table-container {
    max-width: 100%;
    overflow-x: auto;
    margin-bottom: 50px;
}

.registration-table {
    width: 100%;
    border-collapse: collapse;
    text-align: left;
}

.registration-table th,
.registration-table td {
    padding: 15px 20px;
    border: 1px solid #ffffff;
    font-family: 'Arial', sans-serif;
    font-size: 16px;
}

.registration-table th {
    background-color: #ff9800;
    color: #1e2a38;
    font-weight: bold;
}

.registration-table td.center {
    text-align: center;
}

.registration-table td {
    background-color: #2c3e50;
}

/* Registration Process Section */
.registration-process-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 20px;
    background-color: #2c3e50;
    border-radius: 10px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

.registration-process-container p {
    font-size: 18px;
    line-height: 1.6;
    margin-bottom: 15px;
    color: #ffffff;
}

.registration-process-container ol {
    margin-left: 20px;
    padding-left: 10px;
}

.registration-process-container ol li {
    margin-bottom: 15px;
}

.registration-process-container a {
    color: #ff9800;
    text-decoration: none;
}

.registration-process-container .highlighted-text {
    color: #e74c3c;
    font-weight: bold;
    font-size: 18px;
}

HTML

<section id="registration-fees" class="registration-section">
    <h2 class="registration-heading">Registration Fees</h2>
    <div class="registration-table-container">
        <table class="registration-table">
            <thead>
                <tr>
                    <th colspan="2">Category</th>
                    <th colspan="2">North East India</th>
                    <th colspan="2">India (Excluding North East India)</th>
                    <th colspan="2">Abroad</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td rowspan="2">Authors</td>
                    <td>IEEE Member</td>
                    <td>Non-IEEE Member</td>
                    <td>IEEE Member</td>
                    <td>Non-IEEE Member</td>
                    <td>IEEE Member</td>
                    <td>Non-IEEE Member</td>
                </tr>
                <tr>
                    <td>Rs. 3000</td>
                    <td>Rs. 4000</td>
                    <td>Rs. 3500</td>
                    <td>Rs. 4500</td>
                    <td>$150</td>
                    <td>$200</td>
                </tr>
                <tr>
                    <td>Delegates from Academia/Industry</td>
                    <td>Rs. 4500</td>
                    <td>Rs. 5500</td>
                    <td>Rs. 5000</td>
                    <td>Rs. 6000</td>
                    <td>$250</td>
                    <td>$300</td>
                </tr>
                <tr>
                    <td rowspan="2">Attendees (Non-Author)</td>
                    <td colspan="2" class="center">With Conference Kit</td>
                    <td colspan="2" class="center">Without Conference Kit</td>
                    <!-- <td>$250</td>
                    <td>$300</td> -->
                    <td colspan="2" rowspan="1" class="center">With Conference Kit</td>
                    
                </tr>
                <tr>
                    <td>Rs. 1000</td>
                    <td>Rs. 1200</td>
                    <td>Rs. 500</td>
                    <td>Rs. 600</td>
                    <td>$50</td> 
                    <td>$75</td> 
                </tr>
                
            </tbody>
        </table>
    </div>



HTML


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ISACC 2025</title>
    <link rel="stylesheet" href="../assets/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">

</head>
<body>

    <!-- Header Section -->
     <!-- Header Section -->
      <!-- Header Section -->

      <header>
        <div class="container">
            <!-- Logo Section -->
            <div class="logo-container">
                <a href="https://www.aus.ac.in/" target="_blank">
                    <img src="../assets/images/aus-logo.png" alt="Assam University Logo" class="logo">
                </a>
                <a href="index.html">
                    <img src="../assets/images/isacc-logo.png" alt="ISACC Logo" class="logo">
                </a>
            </div>
    
            <!-- Navigation Section -->
             <div>
            <nav  class="main-nav">
                <ul>
                    <li><a href="../index.html">Home</a></li>
                    <li><a href="./about.html">About</a></li>
                    <li><a href="./speakers.html">Speakers</a></li>
                    <li class="dropdown">
                        <a class="dropbtn">ISACC 2025</a>
                        <div class="dropdown-content">
                            <a href="./commitees.html">Committees</a>
                            <a href="./tracks.html">Tracks</a>
                            <a href="./submission.html">Submission</a>
                            <a href="./registration.html">Registration and Fees</a>
                            <a href="./author.html">Author Notification</a>
                            <a href="./dates.html">Important Dates</a>
                            <a href="./gallery.html">Gallery</a>
                        </div>
                    </li>
                    <li><a href="./schedule.html">Schedule</a></li>
                    <li><a href="./sponsors.html">Technical Sponsors</a></li>
                    <li class="dropdown">
                        <a class="dropbtn">Past Conferences</a>
                        <div class="dropdown-content">
                            <a href="https://ieeexplore.ieee.org/xpl/conhome/10083315/proceeding">ISACC 2023</a>
                            <a href="https://ieeexplore.ieee.org/xpl/conhome/7368273/proceeding">ISACC 2015</a>
                        </div>
                    </li>
                    <li><a href="./venue.html">Venue and Contact</a></li>
                </ul>
            </nav>
            <!-- Mobile Menu Toggle -->
            <div class="menu-toggle">☰</div>
        </div>
        </div>
    </header>

<!-- registration ooooooooooooo start -->

    <section id="registration-fees" class="registration-section">
    <h2 id="isacc-2025-heading">ISACC 2025</h2>
    <h3 id="registration-fees-heading">Registration Fees:</h3>
    <table class="registration-fees-table">
        <thead>
            <tr>
                <th class="category-heading">Category</th>
                <th>North East India</th>
                <th>India (Excluding North East India)</th>
                <th>Abroad</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Student/Research Scholar (IEEE Member)</td>
                <td>Rs. 3000</td>
                <td>Rs. 3500</td>
                <td>$150</td>
            </tr>
            <tr>
                <td>Student/Research Scholar (Non-IEEE Member)</td>
                <td>Rs. 4000</td>
                <td>Rs. 4500</td>
                <td>$200</td>
            </tr>
            <tr>
                <td>Delegates from Academia/Industry (IEEE Member)</td>
                <td>Rs. 4500</td>
                <td>Rs. 5000</td>
                <td>$250</td>
            </tr>
            <tr>
                <td>Delegates from Academia/Industry (Non-IEEE Member)</td>
                <td>Rs. 5500</td>
                <td>Rs. 6000</td>
                <td>$300</td>
            </tr>
            <tr>
                <td rowspan="2">Attendees (Non-Author)</td>
                <td>With Conference Kit: Rs. 1000 (IEEE Member), Rs. 1200 (Non-IEEE Member)</td>
                <td>With Conference Kit: Rs. 1200 (IEEE Member), Rs. 1400 (Non-IEEE Member)</td>
                <td>With Conference Kit: $50 (IEEE Member), $75 (Non-IEEE Member)</td>
            </tr>
            <tr>
                <td>Without Conference Kit: Rs. 500 (IEEE Member), Rs. 700 (Non-IEEE Member)</td>
                <td>Without Conference Kit: Rs. 600 (IEEE Member), Rs. 800 (Non-IEEE Member)</td>
                <td>Without Conference Kit: --- </td>
            </tr>
        </tbody>
    </table>
</section>

<section>



    <h2 class="registration-process-heading">Registration Process</h2>
    <div class="registration-process-container">
        <p>Prepare the Camera Ready Paper incorporating all the reviewer comments.</p>
        <p>Prepare the reviewer response sheet.</p>
        <p>Prepare the copyright form <a href="#">Click here to download the copyright form</a>.</p>
        <!-- <p class="highlighted-text">Registration payment deadline have been extended till 27th January, 2023</p> -->
        <ol>
            <li>
                Authors and participants are required to deposit the registration fees in online mode
                (NEFT/IMPS/NETBANKING/UPI) to the following account:
                <ul>
                    <li><strong>A. Name of the account:</strong> ASSAM UNIVERSITY PROJECT A/C II</li>
                    <li><strong>B. Account Number:</strong> 20050110035450</li>
                    <li><strong>C. Bank Branch:</strong> UCO BANK, ASSAM UNIVERSITY BRANCH</li>
                    <li><strong>D. IFSC CODE:</strong> UCBA0002005</li>
                </ul>
            </li>
            <li>
                Authors and participants are required to write a remark/comment as "ISACC REGISTRATION FEES - PAPER ID (PAPER ID indicates the actual paper id of the manuscript.)" during the transaction.
            </li>
            <li>
                Authors and participants are required to keep a copy(screenshot)/e-receipt of the payment proof of successful transaction. Also note down the transaction id for future reference.
            </li>
            <li>
                <a href="#">Click here to complete the registration process.</a>
            </li>
        </ol>
    </div>
</section>




<!-- registration ooooooooooooo end -->

<!-- Footer Section -->
<!-- Footer Section -->
<!-- Footer Section -->
<!-- Footer Section -->
<footer>
    <div class="footer-container">
        <div class="footer-left">
            <p>&copy; 2024 Assam University, India | All Rights Reserved</p>
            <p>Department of Computer Science & Engineering, Assam University</p>
        </div>
        <div class="footer-center">
            <!-- Back to Top Button -->
            <a href="#top" class="back-to-top">Back to Top</a>
            <!-- Visitor Counter -->
            <div class="visitor-counter">
                <a href="https://www.free-counters.org/">Get free Counters</a>
                <script type="text/javascript" src="https://www.freevisitorcounters.com/auth.php?id=97ee0afb70787acfcaeb0105769f40f77c44f6be"></script>
                <script type="text/javascript" src="https://www.freevisitorcounters.com/en/home/counter/1227508/t/5"></script>
            </div>
        </div>
        <div class="footer-right">
            <h3>Location</h3>
            <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d14501.563105449173!2d92.75134!3d24.67909!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x374e3824e8e868b9%3A0x78c2682ac4badc2b!2sDepartment%20of%20Computer%20Science%20%26%20Engineering%2C%20Assam%20University!5e0!3m2!1sen!2sin!4v1725109964004!5m2!1sen!2sin" width="250" height="200" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </div>
    </div>
</footer>








<script src="../assets/js/script.js"></script>
</body>
</html>





    
