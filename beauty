<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ghana Beauty Pageant - Vote Now</title>
    <style>
        :root {
            --primary: #6a11cb;
            --primary-light: #7d3cff;
            --secondary: #ff4d94;
            --accent: #00c9ff;
            --gh-green: #006b3f;
            --gh-yellow: #fcd116;
            --gh-red: #ce1126;
            --dark: #2d3436;
            --light: #f8f9fa;
            --gray: #636e72;
            --success: #00b894;
            --danger: #d63031;
            --warning: #fdcb6e;
            --info: #0984e3;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', 'Segoe UI', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: var(--dark);
            line-height: 1.6;
            min-height: 100vh;
            padding-bottom: 2rem;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            color: var(--dark);
            padding: 1.5rem 0;
            text-align: center;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            margin-bottom: 2rem;
            position: relative;
            border-radius: 0 0 20px 20px;
        }
        
        .logo {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            margin-bottom: 10px;
        }
        
        .crown-icon {
            font-size: 2rem;
            color: var(--primary);
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        
        header p {
            font-size: 1.1rem;
            color: var(--gray);
            max-width: 600px;
            margin: 0 auto;
        }
        
        .tabs {
            display: flex;
            justify-content: center;
            margin-bottom: 2rem;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            padding: 8px;
            width: fit-content;
            margin: 0 auto 2rem;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
            gap: 5px;
        }
        
        .tab-btn {
            padding: 12px 30px;
            border: none;
            background: transparent;
            font-size: 1rem;
            font-weight: 600;
            border-radius: 12px;
            cursor: pointer;
            transition: all 0.3s ease;
            color: var(--gray);
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .tab-btn i {
            font-size: 1.2rem;
        }
        
        .tab-btn.active {
            background: var(--primary);
            color: white;
            box-shadow: 0 4px 15px rgba(106, 17, 203, 0.3);
        }
        
        .tab-content {
            display: none;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 2.5rem;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            margin-bottom: 2rem;
        }
        
        .tab-content.active {
            display: block;
            animation: fadeIn 0.5s ease;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        h2 {
            color: var(--primary);
            margin-bottom: 1.5rem;
            text-align: center;
            font-size: 2rem;
            font-weight: 700;
        }
        
        .section-subtitle {
            text-align: center;
            color: var(--gray);
            margin-bottom: 2rem;
            font-size: 1.1rem;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: var(--dark);
        }
        
        input, select, textarea {
            width: 100%;
            padding: 15px 20px;
            border: 2px solid #e0e0e0;
            border-radius: 12px;
            font-size: 1rem;
            transition: all 0.3s;
            background: white;
        }
        
        input:focus, select:focus, textarea:focus {
            border-color: var(--primary);
            outline: none;
            box-shadow: 0 0 0 3px rgba(106, 17, 203, 0.1);
        }
        
        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            padding: 15px 30px;
            background: var(--primary);
            color: white;
            border: none;
            border-radius: 12px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            text-align: center;
            box-shadow: 0 4px 15px rgba(106, 17, 203, 0.3);
        }
        
        .btn:hover {
            background: var(--primary-light);
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(106, 17, 203, 0.4);
        }
        
        .btn-secondary {
            background: var(--secondary);
            box-shadow: 0 4px 15px rgba(255, 77, 148, 0.3);
        }
        
        .btn-secondary:hover {
            background: #ff6ba8;
            box-shadow: 0 8px 20px rgba(255, 77, 148, 0.4);
        }
        
        .btn-ghana {
            background: var(--gh-green);
            box-shadow: 0 4px 15px rgba(0, 107, 63, 0.3);
        }
        
        .btn-ghana:hover {
            background: #008a4f;
            box-shadow: 0 8px 20px rgba(0, 107, 63, 0.4);
        }
        
        .btn-free {
            background: var(--info);
            box-shadow: 0 4px 15px rgba(9, 132, 227, 0.3);
        }
        
        .btn-free:hover {
            background: #0a94ff;
            box-shadow: 0 8px 20px rgba(9, 132, 227, 0.4);
        }
        
        .participant-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .participant-card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
            transition: all 0.3s ease;
            border: 1px solid #f0f0f0;
        }
        
        .participant-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
        }
        
        .participant-image {
            height: 220px;
            background: linear-gradient(45deg, var(--primary-light), var(--secondary));
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 4rem;
            position: relative;
            overflow: hidden;
        }
        
        .participant-image::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(to bottom, transparent, rgba(0,0,0,0.1));
        }
        
        .participant-country {
            position: absolute;
            top: 15px;
            right: 15px;
            background: rgba(255, 255, 255, 0.9);
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
            color: var(--primary);
            z-index: 1;
        }
        
        .participant-info {
            padding: 1.5rem;
        }
        
        .participant-name {
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
            color: var(--primary);
        }
        
        .participant-details {
            margin-bottom: 1rem;
            color: var(--gray);
        }
        
        .participant-detail {
            display: flex;
            align-items: center;
            gap: 8px;
            margin-bottom: 5px;
        }
        
        .vote-count {
            font-weight: 600;
            color: var(--secondary);
            margin-bottom: 1rem;
            font-size: 1.1rem;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .vote-options {
            display: flex;
            gap: 10px;
        }
        
        .vote-btn {
            flex: 1;
            padding: 12px;
            color: white;
            border: none;
            border-radius: 10px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }
        
        .vote-btn-paid {
            background: var(--primary);
        }
        
        .vote-btn-paid:hover {
            background: var(--primary-light);
        }
        
        .vote-btn-free {
            background: var(--info);
        }
        
        .vote-btn-free:hover {
            background: #0a94ff;
        }
        
        .vote-btn:disabled {
            background: #ccc;
            cursor: not-allowed;
        }
        
        .vote-success {
            color: var(--success);
            font-weight: 600;
            text-align: center;
            margin-top: 1rem;
            display: none;
            padding: 10px;
            background: rgba(0, 184, 148, 0.1);
            border-radius: 10px;
        }
        
        .results-container {
            margin-top: 2rem;
        }
        
        .result-item {
            display: flex;
            align-items: center;
            background: white;
            padding: 1.5rem;
            border-radius: 15px;
            margin-bottom: 1rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s;
        }
        
        .result-item:hover {
            transform: translateX(5px);
        }
        
        .result-rank {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--primary);
            margin-right: 1.5rem;
            width: 50px;
            text-align: center;
        }
        
        .result-info {
            flex-grow: 1;
        }
        
        .result-name {
            font-weight: 700;
            margin-bottom: 0.3rem;
            font-size: 1.2rem;
        }
        
        .result-votes {
            color: var(--secondary);
            font-weight: 600;
        }
        
        .progress-bar {
            height: 10px;
            background: #eee;
            border-radius: 5px;
            margin-top: 0.5rem;
            overflow: hidden;
        }
        
        .progress {
            height: 100%;
            background: linear-gradient(to right, var(--primary), var(--secondary));
            border-radius: 5px;
        }
        
        .phone-voting-guide {
            background: white;
            border-radius: 20px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }
        
        .guide-steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .guide-step {
            text-align: center;
            padding: 2rem 1.5rem;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            border-radius: 15px;
            transition: transform 0.3s;
        }
        
        .guide-step:hover {
            transform: translateY(-5px);
        }
        
        .step-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: var(--primary);
        }
        
        .step-number {
            display: inline-block;
            width: 30px;
            height: 30px;
            background: var(--primary);
            color: white;
            border-radius: 50%;
            line-height: 30px;
            margin-bottom: 1rem;
            font-weight: bold;
        }
        
        .step-title {
            font-weight: 700;
            margin-bottom: 1rem;
            color: var(--dark);
        }
        
        .payment-receiver {
            background: linear-gradient(135deg, var(--gh-green), #008a4f);
            color: white;
            padding: 1.5rem;
            border-radius: 15px;
            text-align: center;
            margin: 2rem 0;
        }
        
        .receiver-number {
            font-size: 2rem;
            font-weight: 700;
            margin: 1rem 0;
            letter-spacing: 2px;
        }
        
        /* Modal Styles */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            z-index: 1000;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        
        .modal-content {
            background: white;
            border-radius: 20px;
            width: 100%;
            max-width: 500px;
            padding: 2.5rem;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.3);
            position: relative;
            animation: modalFadeIn 0.4s ease;
        }
        
        @keyframes modalFadeIn {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }
        
        .close-modal {
            position: absolute;
            top: 20px;
            right: 20px;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--gray);
            background: #f0f0f0;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s;
        }
        
        .close-modal:hover {
            background: var(--danger);
            color: white;
        }
        
        .modal-title {
            color: var(--primary);
            margin-bottom: 1.5rem;
            text-align: center;
            font-size: 1.8rem;
        }
        
        footer {
            text-align: center;
            margin-top: 3rem;
            padding-top: 1.5rem;
            border-top: 1px solid rgba(255, 255, 255, 0.2);
            color: rgba(255, 255, 255, 0.8);
        }
        
        @media (max-width: 768px) {
            .participant-grid {
                grid-template-columns: 1fr;
            }
            
            header h1 {
                font-size: 2rem;
            }
            
            .tabs {
                flex-direction: column;
                width: 100%;
            }
            
            .tab-btn {
                width: 100%;
                margin-bottom: 5px;
            }
            
            .vote-options {
                flex-direction: column;
            }
            
            .guide-steps {
                grid-template-columns: 1fr;
            }
            
            .receiver-number {
                font-size: 1.5rem;
            }
        }
    </style>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <div class="crown-icon">👑</div>
                <h1>Ghana Beauty Pageant</h1>
            </div>
            <p>Vote for your favorite contestants from anywhere in Ghana</p>
        </div>
    </header>
    
    <div class="container">
        <div class="tabs">
            <button class="tab-btn active" data-tab="vote">
                <i class="fas fa-vote-yea"></i> Vote Now
            </button>
            <button class="tab-btn" data-tab="guide">
                <i class="fas fa-mobile-alt"></i> How to Vote
            </button>
            <button class="tab-btn" data-tab="results">
                <i class="fas fa-chart-bar"></i> View Results
            </button>
            <button class="tab-btn" data-tab="add-participant">
                <i class="fas fa-user-plus"></i> Add Participant
            </button>
        </div>
        
        <!-- Vote Tab -->
        <div class="tab-content active" id="vote">
            <h2>Vote for Your Favorite Contestant</h2>
            <p class="section-subtitle">Choose between paid voting (₵2.00 via Mobile Money) or free in-house voting</p>
            
            <div class="form-group">
                <label for="voterLocation"><i class="fas fa-map-marker-alt"></i> Your Location in Ghana</label>
                <select id="voterLocation">
                    <option value="">Select your region</option>
                    <option value="Greater Accra">Greater Accra</option>
                    <option value="Ashanti">Ashanti</option>
                    <option value="Western">Western</option>
                    <option value="Central">Central</option>
                    <option value="Eastern">Eastern</option>
                    <option value="Volta">Volta</option>
                    <option value="Northern">Northern</option>
                    <option value="Brong Ahafo">Brong Ahafo</option>
                    <option value="Upper East">Upper East</option>
                    <option value="Upper West">Upper West</option>
                </select>
            </div>
            
            <div class="participant-grid" id="participantList">
                <!-- Participants will be dynamically added here -->
            </div>
        </div>
        
        <!-- How to Vote Tab -->
        <div class="tab-content" id="guide">
            <h2>How to Vote with Your Phone</h2>
            <p class="section-subtitle">Follow these simple steps to cast your vote using Mobile Money</p>
            
            <div class="phone-voting-guide">
                <div class="guide-steps">
                    <div class="guide-step">
                        <div class="step-number">1</div>
                        <div class="step-icon"><i class="fas fa-user-check"></i></div>
                        <div class="step-title">Select Contestant</div>
                        <p>Choose your favorite contestant and click "Vote with Mobile Money"</p>
                    </div>
                    
                    <div class="guide-step">
                        <div class="step-number">2</div>
                        <div class="step-icon"><i class="fas fa-mobile"></i></div>
                        <div class="step-title">Choose Network</div>
                        <p>Select your mobile money provider (MTN, Vodafone, or AirtelTigo)</p>
                    </div>
                    
                    <div class="guide-step">
                        <div class="step-number">3</div>
                        <div class="step-icon"><i class="fas fa-share-square"></i></div>
                        <div class="step-title">Send Payment</div>
                        <p>Dial *170# and send ₵2.20 to the number below</p>
                    </div>
                    
                    <div class="guide-step">
                        <div class="step-number">4</div>
                        <div class="step-icon"><i class="fas fa-check-circle"></i></div>
                        <div class="step-title">Confirm Vote</div>
                        <p>Enter your phone number to confirm and complete your vote</p>
                    </div>
                </div>
                
                <div class="payment-receiver">
                    <h3><i class="fas fa-money-bill-wave"></i> Send Payment To:</h3>
                    <div class="receiver-number">0541 633 108</div>
                    <p>MTN Mobile Money • ₵2.20 per vote</p>
                </div>
                
                <div class="guide-steps">
                    <div class="guide-step">
                        <div class="step-icon"><i class="fas fa-theater-masks"></i></div>
                        <div class="step-title">In-House Voting</div>
                        <p>Attending the event? Ask staff for a free voting code</p>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Results Tab -->
        <div class="tab-content" id="results">
            <h2>Current Voting Results</h2>
            <p class="section-subtitle">See how your favorite contestants are performing</p>
            
            <div class="results-container" id="resultsContainer">
                <!-- Results will be dynamically added here -->
            </div>
        </div>
        
        <!-- Add Participant Tab -->
        <div class="tab-content" id="add-participant">
            <h2>Add New Participant</h2>
            <p class="section-subtitle">Pageant organizers can add new contestants here</p>
            
            <form id="participantForm">
                <div class="form-group">
                    <label for="participantName"><i class="fas fa-user"></i> Full Name</label>
                    <input type="text" id="participantName" required>
                </div>
                
                <div class="form-group">
                    <label for="participantAge"><i class="fas fa-birthday-cake"></i> Age</label>
                    <input type="number" id="participantAge" min="18" max="35" required>
                </div>
                
                <div class="form-group">
                    <label for="participantCountry"><i class="fas fa-flag"></i> Country</label>
                    <select id="participantCountry" required>
                        <option value="">Select country</option>
                        <option value="Ghana" selected>Ghana</option>
                        <option value="Nigeria">Nigeria</option>
                        <option value="USA">United States</option>
                        <option value="UK">United Kingdom</option>
                        <option value="Other">Other</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="participantTalent"><i class="fas fa-star"></i> Talent</label>
                    <input type="text" id="participantTalent" required>
                </div>
                
                <div class="form-group">
                    <label for="participantBio"><i class="fas fa-file-alt"></i> Short Bio</label>
                    <textarea id="participantBio" rows="4" required></textarea>
                </div>
                
                <button type="submit" class="btn btn-secondary">
                    <i class="fas fa-plus"></i> Add Participant
                </button>
            </form>
        </div>
    </div>
    
    <!-- Payment Modal -->
    <div class="modal" id="paymentModal">
        <div class="modal-content">
            <span class="close-modal" id="closeModal">&times;</span>
            <h2 class="modal-title">Complete Your Vote</h2>
            
            <div class="payment-receiver" style="margin: 1.5rem 0;">
                <h3><i class="fas fa-money-bill-wave"></i> Send Payment To:</h3>
                <div class="receiver-number">0541 633 108</div>
                <p>MTN Mobile Money • ₵2.20 per vote</p>
            </div>
            
            <div class="form-group">
                <label for="phoneNumber"><i class="fas fa-mobile-alt"></i> Your Phone Number</label>
                <input type="tel" id="phoneNumber" placeholder="e.g., 0244 123 456" maxlength="10">
            </div>
            
            <button class="btn btn-ghana" id="confirmVote" style="width: 100%;">
                <i class="fas fa-check-circle"></i> Confirm Vote
            </button>
            
            <div class="vote-success" id="paymentSuccess" style="margin-top: 1.5rem; display: none;">
                <i class="fas fa-check"></i> Your vote has been recorded. Thank you!
            </div>
        </div>
    </div>
    
    <!-- In-House Voting Modal -->
    <div class="modal" id="inHouseModal">
        <div class="modal-content">
            <span class="close-modal" id="closeInHouseModal">&times;</span>
            <h2 class="modal-title">In-House Voting</h2>
            
            <div class="form-group">
                <label for="inHouseCode"><i class="fas fa-key"></i> Enter Voting Code</label>
                <input type="text" id="inHouseCode" placeholder="Enter 6-digit code from staff" maxlength="6">
            </div>
            
            <button class="btn btn-free" id="submitInHouseVote" style="width: 100%;">
                <i class="fas fa-vote-yea"></i> Submit Free Vote
            </button>
            
            <div class="vote-success" id="inHouseSuccess" style="margin-top: 1.5rem; display: none;">
                <i class="fas fa-check"></i> Your free vote has been recorded. Thank you!
            </div>
        </div>
    </div>
    
    <footer class="container">
        <p>Ghana Beauty Pageant Voting System &copy; 2023 | All votes are final</p>
        <p>Powered by Ghana Mobile Money | Receiver: 0541 633 108</p>
    </footer>

    <script>
        // Sample initial participants
        let participants = [
            {
                id: 1,
                name: "Ama Serwaa",
                age: 24,
                country: "Ghana",
                talent: "Traditional Dance",
                bio: "A passionate dancer specializing in Adowa and Kpanlogo dances.",
                votes: 120,
                voters: [],
                paidVotes: 80,
                freeVotes: 40
            },
            {
                id: 2,
                name: "Kwame Asante",
                age: 26,
                country: "Ghana",
                talent: "Spoken Word Poetry",
                bio: "Award-winning poet with performances across West Africa.",
                votes: 95,
                voters: [],
                paidVotes: 60,
                freeVotes: 35
            },
            {
                id: 3,
                name: "Efua Mensah",
                age: 22,
                country: "Ghana",
                talent: "Fashion Design",
                bio: "Creates stunning contemporary African fashion designs.",
                votes: 150,
                voters: [],
                paidVotes: 110,
                freeVotes: 40
            },
            {
                id: 4,
                name: "Kofi Ansah",
                age: 25,
                country: "Ghana",
                talent: "Musical Performance",
                bio: "Multi-instrumentalist specializing in traditional Ghanaian music.",
                votes: 80,
                voters: [],
                paidVotes: 50,
                freeVotes: 30
            }
        ];

        // Current selected participant for voting
        let selectedParticipantId = null;
        // Valid in-house codes (in a real system, these would be generated and validated server-side)
        const validInHouseCodes = ["123456", "654321", "111222", "333444"];

        // Tab functionality
        document.querySelectorAll('.tab-btn').forEach(button => {
            button.addEventListener('click', () => {
                // Remove active class from all buttons and content
                document.querySelectorAll('.tab-btn').forEach(btn => {
                    btn.classList.remove('active');
                });
                document.querySelectorAll('.tab-content').forEach(content => {
                    content.classList.remove('active');
                });
                
                // Add active class to clicked button
                button.classList.add('active');
                
                // Show corresponding content
                const tabId = button.getAttribute('data-tab');
                document.getElementById(tabId).classList.add('active');
                
                // If results tab is clicked, update results
                if (tabId === 'results') {
                    displayResults();
                }
            });
        });

        // Display participants in the voting section
        function displayParticipants() {
            const participantList = document.getElementById('participantList');
            participantList.innerHTML = '';
            
            participants.forEach(participant => {
                const participantCard = document.createElement('div');
                participantCard.className = 'participant-card';
                
                // Generate initials for profile image
                const names = participant.name.split(' ');
                const initials = names[0].charAt(0) + (names[1] ? names[1].charAt(0) : '');
                
                participantCard.innerHTML = `
                    <div class="participant-image">
                        ${initials}
                        <div class="participant-country">${participant.country}</div>
                    </div>
                    <div class="participant-info">
                        <div class="participant-name">${participant.name}</div>
                        <div class="participant-details">
                            <div class="participant-detail">
                                <i class="fas fa-birthday-cake"></i>
                                <span>Age: ${participant.age}</span>
                            </div>
                            <div class="participant-detail">
                                <i class="fas fa-star"></i>
                                <span>Talent: ${participant.talent}</span>
                            </div>
                            <div class="participant-detail">
                                <i class="fas fa-info-circle"></i>
                                <span>${participant.bio}</span>
                            </div>
                        </div>
                        <div class="vote-count">
                            <i class="fas fa-chart-line"></i>
                            Total Votes: ${participant.votes} (Paid: ${participant.paidVotes}, Free: ${participant.freeVotes})
                        </div>
                        <div class="vote-options">
                            <button class="vote-btn vote-btn-paid" data-id="${participant.id}" data-type="paid">
                                <i class="fas fa-mobile-alt"></i> Vote with Mobile Money (₵2)
                            </button>
                            <button class="vote-btn vote-btn-free" data-id="${participant.id}" data-type="free">
                                <i class="fas fa-theater-masks"></i> Free In-House Vote
                            </button>
                        </div>
                        <div class="vote-success" id="success-${participant.id}">
                            <i class="fas fa-check"></i> Vote submitted successfully!
                        </div>
                    </div>
                `;
                
                participantList.appendChild(participantCard);
            });
            
            // Add event listeners to vote buttons
            document.querySelectorAll('.vote-btn-paid').forEach(button => {
                button.addEventListener('click', function() {
                    const participantId = parseInt(this.getAttribute('data-id'));
                    const location = document.getElementById('voterLocation').value;
                    
                    if (!location) {
                        alert('Please select your location before voting.');
                        return;
                    }
                    
                    selectedParticipantId = participantId;
                    openPaymentModal(participantId);
                });
            });
            
            document.querySelectorAll('.vote-btn-free').forEach(button => {
                button.addEventListener('click', function() {
                    const participantId = parseInt(this.getAttribute('data-id'));
                    const location = document.getElementById('voterLocation').value;
                    
                    if (!location) {
                        alert('Please select your location before voting.');
                        return;
                    }
                    
                    selectedParticipantId = participantId;
                    openInHouseModal(participantId);
                });
            });
        }

        // Open payment modal
        function openPaymentModal(participantId) {
            // Reset modal state
            document.getElementById('phoneNumber').value = '';
            document.getElementById('paymentSuccess').style.display = 'none';
            
            // Show modal
            document.getElementById('paymentModal').style.display = 'flex';
        }

        // Open in-house voting modal
        function openInHouseModal(participantId) {
            // Reset modal state
            document.getElementById('inHouseCode').value = '';
            document.getElementById('inHouseSuccess').style.display = 'none';
            
            // Show modal
            document.getElementById('inHouseModal').style.display = 'flex';
        }

        // Close modals
        document.getElementById('closeModal').addEventListener('click', function() {
            document.getElementById('paymentModal').style.display = 'none';
        });

        document.getElementById('closeInHouseModal').addEventListener('click', function() {
            document.getElementById('inHouseModal').style.display = 'none';
        });

        // Confirm payment vote
        document.getElementById('confirmVote').addEventListener('click', function() {
            const phoneNumber = document.getElementById('phoneNumber').value;
            
            if (!validatePhoneNumber(phoneNumber)) {
                alert('Please enter a valid Ghanaian phone number (e.g., 0244 123 456)');
                return;
            }
            
            // Show success message
            document.getElementById('paymentSuccess').style.display = 'block';
            
            // Record the paid vote
            const location = document.getElementById('voterLocation').value;
            voteForParticipant(selectedParticipantId, location, 'paid');
            
            // Close modal after 2 seconds
            setTimeout(() => {
                document.getElementById('paymentModal').style.display = 'none';
            }, 2000);
        });

        // Validate phone number
        function validatePhoneNumber(phoneNumber) {
            // Remove any non-digit characters
            const cleanNumber = phoneNumber.replace(/\D/g, '');
            
            // Check length
            if (cleanNumber.length !== 10) {
                return false;
            }
            
            // Check Ghanaian prefixes
            const prefixes = ['024', '054', '055', '059', '020', '050', '027', '057', '026', '056'];
            return prefixes.some(prefix => cleanNumber.startsWith(prefix));
        }

        // Submit in-house vote
        document.getElementById('submitInHouseVote').addEventListener('click', function() {
            const code = document.getElementById('inHouseCode').value;
            
            if (!code) {
                alert('Please enter the in-house voting code');
                return;
            }
            
            if (!validInHouseCodes.includes(code)) {
                alert('Invalid voting code. Please check and try again.');
                return;
            }
            
            // Show success message
            document.getElementById('inHouseSuccess').style.display = 'block';
            
            // Record the free vote
            const location = document.getElementById('voterLocation').value;
            voteForParticipant(selectedParticipantId, location, 'free');
            
            // Close modal after 2 seconds
            setTimeout(() => {
                document.getElementById('inHouseModal').style.display = 'none';
            }, 2000);
        });

        // Vote for a participant
        function voteForParticipant(participantId, location, voteType) {
            const participant = participants.find(p => p.id === participantId);
            
            // Check if user has already voted from this location
            if (participant.voters.includes(location)) {
                alert(`You have already voted for ${participant.name} from ${location}.`);
                return;
            }
            
            // Add vote
            participant.votes++;
            participant.voters.push(location);
            
            // Track vote type
            if (voteType === 'paid') {
                participant.paidVotes++;
            } else {
                participant.freeVotes++;
            }
            
            // Show success message
            const successMsg = document.getElementById(`success-${participantId}`);
            successMsg.style.display = 'block';
            
            // Update display
            displayParticipants();
            displayResults();
            
            // Hide success message after 3 seconds
            setTimeout(() => {
                successMsg.style.display = 'none';
            }, 3000);
        }

        // Display results
        function displayResults() {
            const resultsContainer = document.getElementById('resultsContainer');
            resultsContainer.innerHTML = '';
            
            // Sort participants by votes (descending)
            const sortedParticipants = [...participants].sort((a, b) => b.votes - a.votes);
            
            // Calculate total votes
            const totalVotes = sortedParticipants.reduce((sum, participant) => sum + participant.votes, 0);
            
            sortedParticipants.forEach((participant, index) => {
                const percentage = totalVotes > 0 ? (participant.votes / totalVotes) * 100 : 0;
                
                const resultItem = document.createElement('div');
                resultItem.className = 'result-item';
                resultItem.innerHTML = `
                    <div class="result-rank">${index + 1}</div>
                    <div class="result-info">
                        <div class="result-name">${participant.name} (${participant.country})</div>
                        <div class="result-votes">${participant.votes} votes (${percentage.toFixed(1)}%)</div>
                        <div style="font-size: 0.9rem; color: #666;">
                            <i class="fas fa-mobile-alt"></i> Paid: ${participant.paidVotes} | 
                            <i class="fas fa-theater-masks"></i> Free: ${participant.freeVotes}
                        </div>
                        <div class="progress-bar">
                            <div class="progress" style="width: ${percentage}%"></div>
                        </div>
                    </div>
                `;
                
                resultsContainer.appendChild(resultItem);
            });
        }

        // Add new participant
        document.getElementById('participantForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const name = document.getElementById('participantName').value;
            const age = document.getElementById('participantAge').value;
            const country = document.getElementById('participantCountry').value;
            const talent = document.getElementById('participantTalent').value;
            const bio = document.getElementById('participantBio').value;
            
            // Create new participant
            const newParticipant = {
                id: participants.length > 0 ? Math.max(...participants.map(p => p.id)) + 1 : 1,
                name,
                age: parseInt(age),
                country,
                talent,
                bio,
                votes: 0,
                voters: [],
                paidVotes: 0,
                freeVotes: 0
            };
            
            participants.push(newParticipant);
            
            // Reset form
            this.reset();
            
            // Show success message
            alert(`${name} has been added to the pageant successfully!`);
            
            // Update participants display if we're on the vote tab
            if (document.getElementById('vote').classList.contains('active')) {
                displayParticipants();
            }
        });

        // Initialize the page
        displayParticipants();
        displayResults();
    </script>
</body>
</html>
