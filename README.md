# clipgenius-ai
<!DOCTYPE html>
<html lang="en">
<head>
    <base target="_self">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ClipGenius AI | Convert YouTube Videos to Shorts</title>
    <meta name="description" content="AI-powered platform that converts long YouTube videos into engaging shorts with captions, descriptions, and hashtags.  Auto-upload to social media. ">
    <meta name="keywords" content="AI video editor, YouTube shorts, social media upload, video converter, hashtag generator">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="styles.css">
</head>
<body class="min-h-screen bg-gray-50 text-gray-800">
    <!-- Header & Navigation -->
    <header class="sticky top-0 z-50 bg-white shadow-sm">
        <nav class="container mx-auto px-4 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-2">
                    <div class="w-10 h-10 rounded-lg gradient-bg flex items-center justify-center">
                        <i class="fas fa-cut text-white text-xl"></i>
                    </div>
                    <span class="text-2xl font-bold text-gray-900">ClipGenius<span class="text-primary">AI</span></span>
                </div>
                
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#" class="text-gray-700 hover:text-primary font-medium transition-colors">Home</a>
                    <a href="#" class="text-gray-700 hover:text-primary font-medium transition-colors">Features</a>
                    <a href="#" class="text-gray-700 hover:text-primary font-medium transition-colors">Pricing</a>
                    <a href="#" class="text-gray-700 hover:text-primary font-medium transition-colors">How It Works</a>
                </div>
                
                <div class="flex items-center space-x-4">
                    <button class="hidden md:inline-flex items-center px-4 py-2 rounded-lg text-primary border border-primary hover:bg-primary hover:text-white transition-colors">
                        <i class="fas fa-sign-in-alt mr-2"></i>Sign In
                    </button>
                    <button class="inline-flex items-center px-6 py-3 rounded-lg gradient-bg text-white font-medium hover:opacity-90 transition-opacity">
                        <i class="fas fa-rocket mr-2"></i>Get Started Free
                    </button>
                    <button class="md:hidden text-gray-700">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <main>
        <section class="gradient-bg text-white py-16 md:py-24">
            <div class="container mx-auto px-4">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                    <div>
                        <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold mb-6">
                            Turn Long Videos Into <span class="text-accent">Viral Shorts</span> With AI
                        </h1>
                        <p class="text-xl mb-8 opacity-90">
                            Automatically convert YouTube videos into engaging shorts with AI-generated captions, descriptions, and trending hashtags.  Connect social accounts for instant uploads.
                        </p>
                        <div class="flex flex-col sm: flex-row gap-4">
                            <div class="relative flex-grow">
                                <input 
                                    type="text" 
                                    placeholder="Paste YouTube URL here..." 
                                    class="w-full px-6 py-4 rounded-lg text-gray-900 placeholder-gray-500 focus:outline-none focus:ring-2 focus:ring-primary"
                                >
                                <button class="absolute right-2 top-2 px-6 py-2 bg-primary text-white rounded-lg hover: bg-primary-dark transition-colors">
                                    Analyze
                                </button>
                            </div>
                            <button class="px-8 py-4 bg-accent text-white rounded-lg font-medium hover:bg-yellow-600 transition-colors flex items-center justify-center">
                                <i class="fas fa-magic mr-2"></i>Try AI Demo
                            </button>
                        </div>
                        <div class="mt-8 flex items-center space-x-6">
                            <div class="flex items-center">
                                <i class="fas fa-check-circle text-secondary mr-2"></i>
                                <span>No Watermark</span>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-check-circle text-secondary mr-2"></i>
                                <span>Auto Captions</span>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-check-circle text-secondary mr-2"></i>
                                <span>Social Upload</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="relative">
                        <div class="glass-effect rounded-2xl p-6">
                            <div class="video-preview bg-black rounded-xl overflow-hidden mb-4">
                                <div class="relative h-full flex items-center justify-center">
                                    <div class="absolute inset-0 flex items-center justify-center">
                                        <div class="w-20 h-20 rounded-full bg-primary flex items-center justify-center animate-pulse-slow">
                                            <i class="fas fa-play text-white text-2xl"></i>
                                        </div>
                                    </div>
                                    <div class="absolute bottom-4 left-4 right-4">
                                        <div class="bg-gradient-to-t from-black to-transparent p-4">
                                            <div class="text-white font-bold text-lg">AI Generated Caption</div>
                                            <div class="text-gray-300 text-sm">This is the most amazing part! </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="space-y-4">
                                <div>
                                    <div class="text-sm text-gray-300 mb-1">Generated Description</div>
                                    <div class="text-white bg-dark-light p-3 rounded-lg text-sm">
                                        "Watch the most epic moments from this 2-hour tutorial condensed into 60 seconds!  #shorts #tutorial #viral"
                                    </div>
                                </div>
                                <div class="flex flex-wrap gap-2">
                                    <span class="px-3 py-1 bg-primary rounded-full text-xs">#viral</span>
                                    <span class="px-3 py-1 bg-primary rounded-full text-xs">#shorts</span>
                                    <span class="px-3 py-1 bg-primary rounded-full text-xs">#trending</span>
                                    <span class="px-3 py-1 bg-primary rounded-full text-xs">+5 more</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- How It Works -->
        <section class="py-16 bg-white">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">How It Works in 4 Simple Steps</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="text-center p-6 rounded-xl border border-gray-200 hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 rounded-full bg-primary/10 text-primary flex items-center justify-center text-2xl font-bold mx-auto mb-4">1</div>
                        <h3 class="text-xl font-bold mb-3">Paste YouTube URL</h3>
                        <p class="text-gray-600">Copy and paste any YouTube video link.  Our AI will analyze the content automatically.</p>
                    </div>
                    <div class="text-center p-6 rounded-xl border border-gray-200 hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 rounded-full bg-secondary/10 text-secondary flex items-center justify-center text-2xl font-bold mx-auto mb-4">2</div>
                        <h3 class="text-xl font-bold mb-3">AI Selects Best Clips</h3>
                        <p class="text-gray-600">AI identifies the most engaging moments and creates perfect short-form clips.</p>
                    </div>
                    <div class="text-center p-6 rounded-xl border border-gray-200 hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 rounded-full bg-accent/10 text-accent flex items-center justify-center text-2xl font-bold mx-auto mb-4">3</div>
                        <h3 class="text-xl font-bold mb-3">Add Captions & Hashtags</h3>
                        <p class="text-gray-600">Automatically generate catchy captions, descriptions, and trending hashtags. </p>
                    </div>
                    <div class="text-center p-6 rounded-xl border border-gray-200 hover:shadow-lg transition-shadow">
                        <div class="w-16 h-16 rounded-full bg-purple-500/10 text-purple-500 flex items-center justify-center text-2xl font-bold mx-auto mb-4">4</div>
                        <h3 class="text-xl font-bold mb-3">Upload to Social Media</h3>
                        <p class="text-gray-600">Connect your accounts and upload directly to YouTube Shorts, TikTok, Instagram Reels. </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Social Media Integration -->
        <section class="py-16 bg-gray-50">
            <div class="container mx-auto px-4">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                    <div>
                        <h2 class="text-3xl md: text-4xl font-bold mb-6">Connect & Upload to All Platforms</h2>
                        <p class="text-gray-600 mb-8">
                            Link your social media accounts once and upload your AI-generated shorts directly to multiple platforms simultaneously.  Save hours of manual work. 
                        </p>
                        
                        <div class="space-y-6" id="social-platforms-container">
                            <!-- Generated dynamically by JS -->
                        </div>
                    </div>
                    
                    <div class="relative">
                        <div class="bg-white rounded-2xl shadow-xl p-8">
                            <h3 class="text-2xl font-bold mb-6">Connected Accounts</h3>
                            <div class="space-y-4 mb-8">
                                <div class="flex items-center justify-between p-4 bg-gray-50 rounded-lg">
                                    <div class="flex items-center">
                                        <i class="fab fa-youtube text-red-600 text-xl mr-3"></i>
                                        <span>YouTube Channel</span>
                                    </div>
                                    <span class="text-green-600 text-sm font-medium">
                                        <i class="fas fa-check-circle mr-1"></i>Connected
                                    </span>
                                </div>
                                <div class="flex items-center justify-between p-4 bg-gray-50 rounded-lg">
                                    <div class="flex items-center">
                                        <i class="fab fa-tiktok text-black text-xl mr-3"></i>
                                        <span>TikTok Account</span>
                                    </div>
                                    <span class="text-gray-500 text-sm">Not Connected</span>
                                </div>
                                <div class="flex items-center justify-between p-4 bg-gray-50 rounded-lg">
                                    <div class="flex items-center">
                                        <i class="fab fa-instagram text-purple-600 text-xl mr-3"></i>
                                        <span>Instagram Profile</span>
                                    </div>
                                    <span class="text-green-600 text-sm font-medium">
                                        <i class="fas fa-check-circle mr-1"></i>Connected
                                    </span>
                                </div>
                            </div>
                            
                            <div class="bg-primary/5 border border-primary/20 rounded-xl p-6">
                                <h4 class="font-bold text-primary mb-3">Auto-Upload Settings</h4>
                                <div class="space-y-3">
                                    <label class="flex items-center">
                                        <input type="checkbox" class="mr-3 rounded text-primary" checked>
                                        <span>Upload to all connected platforms</span>
                                    </label>
                                    <label class="flex items-center">
                                        <input type="checkbox" class="mr-3 rounded text-primary" checked>
                                        <span>Schedule posts for optimal times</span>
                                    </label>
                                    <label class="flex items-center">
                                        <input type="checkbox" class="mr-3 rounded text-primary">
                                        <span>Auto-generate platform-specific captions</span>
                                    </label>
                                </div>
                                <button class="w-full mt-6 py-3 bg-primary text-white rounded-lg font-medium hover:bg-primary-dark transition-colors">
                                    Save Settings
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- AI Features -->
        <section class="py-16 bg-white">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Powerful AI Features</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8" id="ai-features-container">
                    <!-- Generated dynamically by JS -->
                </div>
            </div>
        </section>

        <!-- Video Processing Demo -->
        <section class="py-16 bg-gray-50">
            <div class="container mx-auto px-4">
                <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Process Your First Video</h2>
                
                <div class="max-w-4xl mx-auto bg-white rounded-2xl shadow-xl overflow-hidden">
                    <div class="p-8 border-b border-gray-200">
                        <div class="flex items-center justify-between mb-6">
                            <h3 class="text-2xl font-bold">Video Processing Dashboard</h3>
                            <div class="flex items-center space-x-2">
                                <div class="w-3 h-3 rounded-full bg-green-500"></div>
                                <span class="text-sm text-gray-600">AI Processing Ready</span>
                            </div>
                        </div>
                        
                        <div class="mb-8">
                            <label class="block text-gray-700 mb-2 font-medium">YouTube Video URL</label>
                            <div class="flex space-x-4">
                                <input 
                                    type="text" 
                                    placeholder="https://www.youtube.com/watch?v=..." 
                                    class="flex-grow px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus: ring-2 focus:ring-primary"
                                    value="https://www.youtube.com/watch?v=dQw4w9WgXcQ"
                                >
                                <button class="px-6 py-3 bg-primary text-white rounded-lg font-medium hover:bg-primary-dark transition-colors" data-action="process-video">
                                    Process Video
                                </button>
                            </div>
                        </div>
                        
                        <div class="space-y-6">
                            <div>
                                <div class="flex justify-between mb-2">
                                    <span class="text-gray-700">Video Analysis Progress</span>
                                    <span class="text-primary font-medium" id="progress-text">65%</span>
                                </div>
                                <div class="h-2 bg-gray-200 rounded-full overflow-hidden">
                                    <div class="h-full bg-primary rounded-full" id="progress-bar" style="width: 65%"></div>
                                </div>
                            </div>
                            
                            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                                <div class="p-4 bg-gray-50 rounded-lg">
                                    <div class="text-sm text-gray-500 mb-1">Video Duration</div>
                                    <div class="text-xl font-bold">2: 45:18</div>
                                </div>
                                <div class="p-4 bg-gray-50 rounded-lg">
                                    <div class="text-sm text-gray-500 mb-1">Potential Clips</div>
                                    <div class="text-xl font-bold">12</div>
                                </div>
                                <div class="p-4 bg-gray-50 rounded-lg">
                                    <div class="text-sm text-gray-500 mb-1">Processing Time</div>
                                    <div class="text-xl font-bold">~45s</div>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="p-8">
                        <h4 class="text-xl font-bold mb-6">Generated Shorts Preview</h4>
                        <div class="grid grid-cols-1 md: grid-cols-3 gap-6" id="clips-container">
                            <!-- Generated dynamically by JS -->
                        </div>
                        
                        <div class="mt-8 flex justify-between items-center flex-wrap gap-4">
                            <div>
                                <h5 class="font-bold mb-2">Upload to Connected Accounts</h5>
                                <div class="flex space-x-2">
                                    <button class="px-4 py-2 bg-red-600 text-w
/* Custom Tailwind Configuration */
: root {
    --primary:  #6366f1;
    --primary-dark: #4f46e5;
    --secondary: #10b981;
    --accent: #f59e0b;
    --dark:  #1f2937;
    --dark-light: #374151;
}

. gradient-bg {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

. glass-effect {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.2);
}

.video-preview {
    aspect-ratio: 9/16;
}

.progress-ring {
    transform: rotate(-90deg);
}

.progress-ring__circle {
    stroke-dasharray: 283;
    stroke-dashoffset:  283;
    transition: stroke-dashoffset 0.5s ease;
}

/* Animation configurations */
@keyframes float {
    0%, 100% {
        transform: translateY(0);
    }
    50% {
        transform: translateY(-20px);
    }
}

.animate-float {
    animation: float 6s ease-in-out infinite;
}

. animate-pulse-slow {
    animation: pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}
// Main Application Logic

// Initialize application
document.addEventListener("DOMContentLoaded", function() {
    initializeApp();
    renderDynamicContent();
    attachEventListeners();
});

// Initialize the application
function initializeApp() {
    console.log("ClipGenius AI initialized");
}

// Render dynamic content from config
function renderDynamicContent() {
    renderSocialPlatforms();
    renderAIFeatures();
    renderGeneratedClips();
}

// Render social platforms section
function renderSocialPlatforms() {
    const container = document.getElementById("social-platforms-container");
    if (!container) return;
    
    container.innerHTML = "";
    
    socialPlatforms.forEach(platform => {
        const platformElement = document.createElement("div");
        platformElement.className = "flex items-center p-4 bg-white rounded-xl shadow-sm";
        platformElement.innerHTML = `
            <div class="w-12 h-12 rounded-full bg-${platform.color}-100 flex items-center justify-center mr-4">
                <i class="fab fa-${platform.icon} text-${platform.color}-600 text-2xl"></i>
            </div>
            <div class="flex-grow">
                <h4 class="font-bold">${platform.name}</h4>
                <p class="text-sm text-gray-500">${platform.description}</p>
            </div>
            <button class="px-4 py-2 ${platform.connected ? "bg-green-100 text-green-700" : "bg-gray-100 text-gray-700"} rounded-lg hover:bg-gray-200 transition-colors connect-btn" data-platform="${platform.name}">
                ${platform.connected ? '<i class="fas fa-check-circle mr-2"></i>Connected' : "Connect"}
            </button>
        `;
        container.appendChild(platformElement);
    });
}

// Render AI features section
function renderAIFeatures() {
    const container = document. getElementById("ai-features-container");
    if (!container) return;
    
    container.innerHTML = "";
    
    const colorMap = {
        1: { bg: "bg-primary/10", text: "text-primary" },
        2: { bg: "bg-secondary/10", text: "text-secondary" },
        3: { bg: "bg-accent/10", text:  "text-accent" }
    };
    
    aiFeatures.forEach(feature => {
        const colors = colorMap[feature.id];
        const featureElement = document.createElement("div");
        featureElement.className = "p-8 rounded-2xl border border-gray-200 hover:border-primary transition-colors";
        featureElement.innerHTML = `
            <div class="w-14 h-14 rounded-xl ${colors.bg} ${colors.text} flex items-center justify-center text-2xl mb-6">
                <i class="fas fa-${feature.icon}"></i>
            </div>
            <h3 class="text-xl font-bold mb-4">${feature.title}</h3>
            <p class="text-gray-600 mb-6">${feature.description}</p>
            <ul class="space-y-2">
                ${feature.features. map(f => `
                    <li class="flex items-center">
                        <i class="fas fa-check text-secondary mr-2"></i>
                        <span>${f}</span>
                    </li>
                `).join('')}
            </ul>
        `;
        container.appendChild(featureElement);
    });
}

// Render generated clips preview
function renderGeneratedClips() {
    const container = document. getElementById("clips-container");
    if (!container) return;
    
    container.innerHTML = "";
    
    generatedClips.forEach(clip => {
        const clipElement = document.createElement("div");
        clipElement.className = "border border-gray-200 rounded-xl overflow-hidden";
        clipElement.innerHTML = `
            <div class="aspect-video bg-gray-900 relative">
                <div class="absolute inset-0 flex items-center justify-center">
                    <div class="w-12 h-12 rounded-full bg-white/20 flex items-center justify-center">
                        <i class="fas fa-play text-white"></i>
                    </div>
                </div>
                <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black to-transparent p-4">
                    <div class="text-white font-medium">${clip.title}</div>
                    <div class="text-gray-300 text-sm">${clip.timeRange}</div>
                </div>
            </div>
            <div class="p-4">
                <div class="text-sm text-gray-500 mb-2">AI Generated Caption</div>
                <div class="text-gray-800 mb-3">"${clip.caption}"</div>
                <div class="flex flex-wrap gap-1">
                    ${clip.hashtags.map(tag => `
                        <span class="px-2 py-1 bg-gray-100 text-gray-700 rounded text-xs">${tag}</span>
                    `).join('')}
                </div>
            </div>
        `;
        container.appendChild(clipElement);
    });
}

// Attach event listeners
function attachEventListeners() {
    // Connect platform buttons
    document.addEventListener("click", (e) => {
        if (e.target. closest("[data-action='process-video']")) {
            handleProcessVideo();
        }
        if (e.target.closest("[data-action='upload-platform']")) {
            handleUploadPlatform(e.target);
        }
        if (e.target.closest("[data-action='upload-all']")) {
            handleUploadAll();
        }
        if (e.target.closest("[data-action='free-trial']")) {
            handleFreeTrial();
        }
        if (e.target.closest("[data-action='watch-demo']")) {
            handleWatchDemo();
        }
        if (e.target.closest(". connect-btn")) {
            handleConnectPlatform(e. target);
        }
    });

    // Navigation links
    document.querySelectorAll("a").forEach(link => {
        link.addEventListener("click", function(e) {
            if (this.getAttribute("href") === "#") {
                e. preventDefault();
            }
        });
    });
}

// Handle video processing
function handleProcessVideo() {
    const progressBar = document.getElementById("progress-bar");
    const progressText = document.getElementById("progress-text");
    const processBtn = document.querySelector("[data-action='process-video']");
    
    if (processBtn) {
        processBtn. innerHTML = '<i class="fas fa-spinner fa-spin mr-2"></i>Processing...';
        processBtn.disabled = true;
    }
    
    let progress = 0;
    const interval = setInterval(() => {
        progress += 5;
        if (progressBar) {
            progressBar. style.width = progress + "%";
        }
        if (progressText) {
            progressText. textContent = progress + "%";
        }
        
        if (progress >= 100) {
            clearInterval(interval);
            if (processBtn) {
                processBtn.innerHTML = '<i class="fas fa-check mr-2"></i>Processing Complete';
                processBtn.classList.remove("bg-primary");
                processBtn.classList.add("bg-green-600");
            }
            alert("Video processing complete! 12 potential clips identified.");
        }
    }, 200);
}

// Handle platform upload
function handleUploadPlatform(button) {
    const platformText = button.textContent. trim().split('\n')[0];
    alert(`Starting upload to ${platformText}...`);
}

// Handle upload all
function handleUploadAll() {
    const uploadBtn = document.querySelector("[data-action='upload-all']");
    if (uploadBtn) {
        uploadBtn.innerHTML = '<i class="fas fa-spinner fa-spin mr-2"></i>Uploading...';
        uploadBtn.disabled = true;
        
        setTimeout(() => {
            uploadBtn. innerHTML = '<i class="fas fa-check mr-2"></i>Upload Complete';
            uploadBtn.classList. remove("bg-secondary");
            uploadBtn.classList. add("bg-green-600");
            alert("All selected clips uploaded successfully to connected platforms!");
        }, 3000);
    }
}

// Handle connect platform
function handleConnectPlatform(button) {
    const platform = button.getAttribute("data-platform");
    button.innerHTML = '<i class="fas fa-spinner fa-spin mr-2"></i>Connecting...';
    button.disabled = true;
    
    setTimeout(() => {
        button.innerHTML = '<i class="fas fa-check-circle mr-2"></i>Connected';
        button.classList.remove("bg-gray-100", "text-gray-700");
        button.classList.add("bg-green-100", "text-green-700");
        alert(platform + " connected successfully!");
    }, 1500);
}

// Handle free trial
function handleFreeTrial() {
    alert("Starting 14-day free trial!  You'll be redirected to signup.");
}

// Handle watch demo
function handleWatchDemo() {
    alert("Loading AI demo with sample video...");
    const urlInput = document.querySelector("input[placeholder*='Paste YouTube URL']");
    if (urlInput) {
        urlInput. value = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";
    }
}
// Application Configuration Data

const socialPlatforms = [
    { 
        "id": 1, 
        "name": "YouTube", 
        "icon": "youtube", 
        "color": "red", 
        "connected": true,
        "description": "Auto-upload with optimized titles and descriptions"
    },
    { 
        "id": 2, 
        "name":  "TikTok", 
        "icon": "tiktok", 
        "color": "black", 
        "connected": false,
        "description": "Upload with trending sounds and hashtags"
    },
    { 
        "id": 3, 
        "name": "Instagram", 
        "icon":  "instagram", 
        "color": "purple", 
        "connected": true,
        "description": "Post directly to Reels with optimized captions"
    }
];

const aiFeatures = [
    {
        "id": 1,
        "title": "Smart Clip Detection",
        "icon": "brain",
        "description": "AI analyzes viewer engagement patterns to identify the most viral-worthy moments.",
        "features": ["Emotion detection", "Audience retention analysis", "Automatic trimming"]
    },
    {
        "id": 2,
        "title": "AI Caption Generation",
        "icon": "closed-captioning",
        "description": "Automatically generate engaging captions that match the video content and trends.",
        "features": ["Multiple caption styles", "Trend analysis integration", "Auto-timing sync"]
    },
    {
        "id": 3,
        "title": "Hashtag Optimization",
        "icon": "hashtag",
        "description": "Generate trending and relevant hashtags based on content and platform algorithms.",
        "features": ["Platform-specific hashtags", "Trend prediction", "Performance analytics"]
    }
];

const generatedClips = [
    {
        "id": 1,
        "title": "Clip #1",
        "timeRange": "0: 45 - 1:15",
        "caption": "You won't believe what happens next! 😱",
        "hashtags": ["#viral", "#shorts", "#funny"]
    },
    {
        "id": 2,
        "title": "Clip #2",
        "timeRange": "3:22 - 3:52",
        "caption": "This trick will save you hours! ⏰",
        "hashtags":  ["#tutorial", "#tips", "#lifehack"]
    },
    {
        "id": 3,
        "title": "Clip #3",
        "timeRange":  "8:15 - 8:45",
        "caption": "The moment everything changed! 🔥",
        "hashtags":  ["#epic", "#moment", "#trending"]
    }
];
# ClipGenius AI - Convert YouTube Videos to Shorts

ClipGenius AI is an intelligent platform that transforms long-form YouTube videos into engaging short-form content optimized for platforms like YouTube Shorts, TikTok, and Instagram Reels.

## Features

- **Smart Clip Detection**: AI analyzes viewer engagement patterns to identify the most viral-worthy moments
- **AI Caption Generation**:  Automatically generate engaging captions that match video content and current trends
- **Hashtag Optimization**: Generate trending and relevant hashtags based on video content
- **Multi-Platform Upload**: Connect and upload directly to YouTube, TikTok, and Instagram
- **Auto-Scheduling**: Schedule posts for optimal engagement times

## Project Structure

```
clipgenius-ai/
├── index.html       # Main HTML file with structure
├── styles.css       # Custom CSS styles
├── config.js        # Configuration data (platforms, features, clips)
├── app.js           # Main application logic
├── README.md        # This file
└── assets/          # (Optional) Images, icons, etc.
```

## Getting Started

1. Clone the repository
2. Open `index.html` in a modern web browser
3. Start using the application

## Browser Requirements

- Modern browser with ES6 support
- JavaScript enabled
- Internet connection for CDN resources

## Technologies Used

- HTML5
- CSS3 with Tailwind CSS
- Vanilla JavaScript (ES6+)
- Font Awesome Icons

## CDN Dependencies

- Tailwind CSS: https://cdn.tailwindcss.com
- Font Awesome 5. 15.3: https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3

## Usage

### Processing a Video

1. Paste a YouTube URL in the input field
2. Click "Process Video"
3. Wait for AI analysis to complete
4. Review generated clips and captions
5. Connect social media accounts
6. Upload to desired platforms

### Connecting Social Platforms

1. Click "Connect" on the desired platform card
2. Authorize the application
3. Select auto-upload preferences
4. Save settings

## Features Details

### Smart Clip Detection
- Emotion detection in video content
- Audience retention analysis
- Automatic trimming to optimal lengths

### AI Caption Generation
- Multiple caption style options
- Trend analysis integration
- Auto-timing synchronization with video

### Hashtag Optimization
- Platform-specific hashtag generation
- Trend prediction algorithms
- Performance analytics tracking

## Color Scheme

- Primary: #6366f1
- Primary Dark: #4f46e5
- Secondary: #10b981
- Accent: #f59e0b
- Dark:  #1f2937

## Future Enhancements

- Backend API integration
- User authentication and profiles
- Video analytics dashboard
- Advanced AI models
- Batch processing capabilities

## License

All rights reserved © 2024 ClipGenius AI

## Support

For issues and questions, please contact support or create an issue in the repository.
