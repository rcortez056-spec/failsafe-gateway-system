<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fail-Safe Gateway System</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Courier New', monospace;
            background: linear-gradient(135deg, #0a0a0a 0%, #1a1a1a 100%);
            color: #00897b;
            padding: 20px;
            min-height: 100vh;
        }

        .container {
            max-width: 2400px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            margin-bottom: 25px;
            border-bottom: 2px solid #00897b;
            padding-bottom: 15px;
        }

        .header h1 {
            font-size: 32px;
            color: #00897b;
            text-shadow: 0 0 15px rgba(0, 255, 0, 0.6);
            letter-spacing: 2px;
            margin-bottom: 5px;
        }

        .header p {
            font-size: 10px;
            color: #4caf50;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .controls {
            text-align: center;
            margin-bottom: 20px;
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
        }

        button {
            background: #00897b;
            color: #000;
            border: none;
            padding: 10px 20px;
            border-radius: 4px;
            font-family: 'Courier New', monospace;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 10px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        button:hover {
            background: #4caf50;
            box-shadow: 0 0 15px rgba(0, 255, 0, 0.6);
        }

        .status-line {
            text-align: center;
            margin-bottom: 15px;
            font-size: 10px;
            color: #00897b;
        }

        .input-section {
            background: rgba(0, 0, 0, 0.85);
            border: 1px solid #00ffff;
            border-radius: 4px;
            padding: 20px;
            margin-bottom: 20px;
        }

        .input-title {
            color: #00ffff;
            font-weight: bold;
            margin-bottom: 15px;
            text-transform: uppercase;
            font-size: 11px;
            border-bottom: 1px solid #00ffff;
            padding-bottom: 8px;
        }

        .form-group {
            margin-bottom: 12px;
        }

        label {
            color: #00897b;
            display: block;
            margin-bottom: 5px;
            font-size: 9px;
            font-weight: bold;
        }

        input {
            background: rgba(0, 0, 0, 0.9);
            border: 1px solid #00897b;
            color: #00897b;
            padding: 8px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
            width: 100%;
            font-size: 9px;
        }

        input:focus {
            outline: none;
            border-color: #4caf50;
            box-shadow: 0 0 10px rgba(0, 255, 0, 0.3);
        }

        .pipeline-container {
            background: rgba(0, 0, 0, 0.85);
            border: 1px solid #00897b;
            border-radius: 4px;
            padding: 20px;
            margin-bottom: 20px;
        }

        .pipeline-title {
            color: #00897b;
            font-weight: bold;
            margin-bottom: 20px;
            text-transform: uppercase;
            font-size: 11px;
            border-bottom: 1px solid #00897b;
            padding-bottom: 8px;
        }

        .phase-container {
            margin-bottom: 30px;
        }

        .phase-title {
            color: #00ffff;
            font-weight: bold;
            margin-bottom: 15px;
            font-size: 10px;
            text-transform: uppercase;
            padding: 8px;
            background: rgba(0, 150, 150, 0.1);
            border-left: 3px solid #00ffff;
        }

        .node {
            background: rgba(0, 100, 100, 0.2);
            border: 1px solid #00ffff;
            border-radius: 4px;
            padding: 12px;
            font-size: 9px;
            margin-bottom: 10px;
        }

        .node-title {
            color: #00ffff;
            font-weight: bold;
            margin-bottom: 6px;
        }

        .node-content {
            color: #00897b;
            font-size: 8px;
            line-height: 1.4;
        }

        .node.processing {
            background: rgba(100, 200, 255, 0.2);
            border-color: #64c8ff;
            animation: pulse 0.8s infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.6; }
        }

        .node.success {
            background: rgba(0, 255, 0, 0.1);
            border-color: #00897b;
        }

        .node.error {
            background: rgba(255, 0, 0, 0.1);
            border-color: #ff0000;
        }

        .dual-path {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-bottom: 20px;
        }

        .path-a, .path-b {
            background: rgba(0, 0, 0, 0.9);
            border-radius: 4px;
            padding: 15px;
        }

        .path-a {
            border: 1px solid #00897b;
        }

        .path-b {
            border: 1px solid #ffaa00;
        }

        .path-title {
            font-weight: bold;
            margin-bottom: 10px;
            padding-bottom: 8px;
            border-bottom: 1px solid;
            font-size: 9px;
            text-transform: uppercase;
        }

        .path-a .path-title {
            color: #00897b;
            border-color: #00897b;
        }

        .path-b .path-title {
            color: #ffaa00;
            border-color: #ffaa00;
        }

        .grid-2col {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-bottom: 20px;
        }

        .panel {
            background: rgba(0, 0, 0, 0.85);
            border: 1px solid #00897b;
            border-radius: 4px;
            padding: 15px;
            font-size: 9px;
        }

        .panel-title {
            color: #00897b;
            font-weight: bold;
            margin-bottom: 12px;
            padding-bottom: 8px;
            border-bottom: 1px solid #00897b;
            text-transform: uppercase;
            font-size: 10px;
        }

        .scrollable {
            max-height: 400px;
            overflow-y: auto;
        }

        .log-entry {
            background: rgba(0, 150, 150, 0.1);
            border-left: 2px solid #00ffff;
            padding: 6px;
            margin-bottom: 6px;
            font-size: 8px;
            opacity: 0;
            animation: slideIn 0.4s ease forwards;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateX(-10px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        .timestamp {
            color: #4caf50;
            font-size: 7px;
        }

        .action {
            color: #00897b;
            font-weight: bold;
        }

        .success {
            color: #00897b;
        }

        .error {
            color: #ff0000;
        }

        .warning {
            color: #ffaa00;
        }

        .info {
            color: #00ffff;
        }

        ::-webkit-scrollbar {
            width: 6px;
        }

        ::-webkit-scrollbar-track {
            background: rgba(0, 0, 0, 0.5);
        }

        ::-webkit-scrollbar-thumb {
            background: #00897b;
            border-radius: 3px;
        }

        .metrics {
            display: grid;
            grid-template-columns: repeat(6, 1fr);
            gap: 10px;
            margin-bottom: 20px;
        }

        .metric-box {
            background: rgba(0, 150, 150, 0.1);
            border: 1px solid #00ffff;
            border-radius: 4px;
            padding: 10px;
            text-align: center;
        }

        .metric-value {
            color: #00897b;
            font-weight: bold;
            font-size: 14px;
        }

        .metric-label {
            color: #4caf50;
            font-size: 7px;
            text-transform: uppercase;
            margin-top: 4px;
        }

        .full-width {
            grid-column: 1 / -1;
        }

        .arrow {
            text-align: center;
            color: #00ffff;
            font-size: 18px;
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🛡️ FAIL-SAFE GATEWAY SYSTEM</h1>
            <p>3-Phase Validation • Dual-Path Routing • Human-in-Loop Fallback</p>
            <div style="margin-top: 10px; font-size: 9px; color: #4caf50;">Built by Ramon Cortez • AI Architect</div>
        </div>

        <div class="input-section">
            <div class="input-title">📥 Phase 1: Input & Data Validation</div>
            <div class="form-group">
                <label>Lead Email (required: must contain @)</label>
                <input type="email" id="lead-email" placeholder="name@company.com">
            </div>
            <div class="form-group">
                <label>Company Name (required: not empty)</label>
                <input type="text" id="company-name" placeholder="e.g., Acme Corp">
            </div>
            <div class="form-group">
                <label>Job Title (required: not empty)</label>
                <input type="text" id="job-title" placeholder="e.g., Sales Director">
            </div>
        </div>

        <div class="controls">
            <button onclick="processClean()">✓ CLEAN PAYLOAD</button>
            <button onclick="processMissingEmail()">✗ MISSING EMAIL</button>
            <button onclick="processMissingCompany()">✗ MISSING COMPANY</button>
            <button onclick="processAPITimeout()">⏱️ API TIMEOUT</button>
            <button onclick="clearAll()">🗑️ RESET</button>
        </div>

        <div class="status-line" id="status-line"></div>

        <div class="metrics">
            <div class="metric-box">
                <div class="metric-value" id="metric-total">0</div>
                <div class="metric-label">Total Payloads</div>
            </div>
            <div class="metric-box">
                <div class="metric-value" id="metric-valid">0</div>
                <div class="metric-label">Valid (Path A)</div>
            </div>
            <div class="metric-box">
                <div class="metric-value" id="metric-invalid">0</div>
                <div class="metric-label">Invalid (Path B)</div>
            </div>
            <div class="metric-box">
                <div class="metric-value" id="metric-timeout">0</div>
                <div class="metric-label">Timeouts</div>
            </div>
            <div class="metric-box">
                <div class="metric-value" id="metric-human-review">0</div>
                <div class="metric-label">Human Review</div>
            </div>
            <div class="metric-box">
                <div class="metric-value" id="metric-database">0</div>
                <div class="metric-label">Database Stored</div>
            </div>
        </div>

        <!-- Phase 1 Visualization -->
        <div class="pipeline-container">
            <div class="pipeline-title">🔄 Pipeline Execution</div>

            <!-- Phase 1 -->
            <div class="phase-container">
                <div class="phase-title">Phase 1: Input & Data Validation</div>
                <div class="node" id="phase1-node">
                    <div class="node-title">🔍 Validation Check</div>
                    <div class="node-content">Checking: lead_email ≠ empty AND contains @ | company_name ≠ empty | job_title ≠ empty</div>
                </div>
            </div>

            <!-- Phase 2: Dual Path -->
            <div class="phase-container">
                <div class="phase-title">Phase 2: Dual Routing Logic</div>
                <div class="dual-path">
                    <div class="path-a">
                        <div class="path-title">✓ Path A: Execution (If Valid)</div>
                        <div class="node" id="path-a-node1">
                            <div class="node-title">Step 4: Enrichment</div>
                            <div class="node-content">Call external enrichment API | Extract company insights</div>
                        </div>
                        <div class="arrow">↓</div>
                        <div class="node" id="path-a-node2">
                            <div class="node-title">Step 5: Timeout Handler</div>
                            <div class="node-content">Max retries: 2 | If success → Output to database</div>
                        </div>
                    </div>
                    <div class="path-b">
                        <div class="path-title">✗ Path B: Fail-Safe (If Invalid OR Timeout)</div>
                        <div class="node" id="path-b-node1">
                            <div class="node-title">Step 6: Fallback Trigger</div>
                            <div class="node-content">Validation failed OR enrichment API timeout</div>
                        </div>
                        <div class="arrow">↓</div>
                        <div class="node" id="path-b-node2">
                            <div class="node-title">Step 7: Fallback Action</div>
                            <div class="node-content">Flag: Status=Requires_Human_Review | Log reason | Alert queue</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Phase 3 -->
            <div class="phase-container">
                <div class="phase-title">Phase 3: Final Output & Documentation</div>
                <div class="node" id="phase3-node">
                    <div class="node-title">✓ Complete</div>
                    <div class="node-content">Step 8: Test with clean/corrupted payloads | Step 9: Export workflow | Step 10: Upload to GitHub</div>
                </div>
            </div>
        </div>

        <!-- Logs -->
        <div class="grid-2col">
            <div class="panel">
                <div class="panel-title">📝 Validation Log</div>
                <div class="scrollable" id="validation-log"></div>
            </div>
            <div class="panel">
                <div class="panel-title">🚀 Execution Log</div>
                <div class="scrollable" id="execution-log"></div>
            </div>
        </div>

        <div class="grid-2col">
            <div class="panel">
                <div class="panel-title">💾 Database (Path A Output)</div>
                <div class="scrollable" id="database-log"></div>
            </div>
            <div class="panel">
                <div class="panel-title">⚠️ Human Review Queue (Path B Output)</div>
                <div class="scrollable" id="review-queue-log"></div>
            </div>
        </div>
    </div>

    <script>
        const state = {
            metrics: {
                total: 0,
                valid: 0,
                invalid: 0,
                timeout: 0,
                humanReview: 0,
                database: 0
            }
        };

        function formatTime() {
            const now = new Date();
            return now.toLocaleTimeString('en-US', { hour12: false }) + '.' + 
                   now.getMilliseconds().toString().padStart(3, '0');
        }

        function generatePayloadId() {
            return 'PAYLOAD-' + Date.now() + '-' + Math.random().toString(36).slice(2, 6).toUpperCase();
        }

        function addLog(panelId, timestamp, label, message, severity = 'info') {
            const container = document.getElementById(panelId);
            const entry = document.createElement('div');
            entry.className = 'log-entry';
            entry.innerHTML = `
                <span class="timestamp">[${timestamp}]</span>
                <span class="action">${label}</span>
                <span class="${severity}">${message}</span>
            `;
            entry.style.animationDelay = Math.random() * 0.2 + 's';
            container.appendChild(entry);
            container.scrollTop = container.scrollHeight;
            
            if (container.children.length > 25) {
                container.removeChild(container.firstChild);
            }
        }

        function updateMetrics() {
            document.getElementById('metric-total').textContent = state.metrics.total;
            document.getElementById('metric-valid').textContent = state.metrics.valid;
            document.getElementById('metric-invalid').textContent = state.metrics.invalid;
            document.getElementById('metric-timeout').textContent = state.metrics.timeout;
            document.getElementById('metric-human-review').textContent = state.metrics.humanReview;
            document.getElementById('metric-database').textContent = state.metrics.database;
        }

        function setNodeStatus(nodeId, status) {
            const node = document.getElementById(nodeId);
            if (node) {
                node.classList.remove('processing', 'success', 'error', 'warning');
                if (status) node.classList.add(status);
            }
        }

        async function processPayload(payload, testType = 'normal') {
            const payloadId = generatePayloadId();
            const timestamp = formatTime();
            
            state.metrics.total++;

            document.getElementById('status-line').textContent = `Processing: ${payloadId}`;

            // PHASE 1: Validation
            setNodeStatus('phase1-node', 'processing');
            const timestamp1 = formatTime();
            addLog('validation-log', timestamp1, 'VALIDATE', `Checking payload: ${payloadId}`);

            await new Promise(r => setTimeout(r, 400));

            let isValid = true;
            let validationErrors = [];

            if (!payload.email || payload.email.trim() === '' || !payload.email.includes('@')) {
                isValid = false;
                validationErrors.push('lead_email is empty or missing @');
                addLog('validation-log', formatTime(), 'FAILED', 'Condition A: lead_email validation FAILED', 'error');
            } else {
                addLog('validation-log', formatTime(), 'PASSED', 'Condition A: lead_email ✓', 'success');
            }

            if (!payload.company || payload.company.trim() === '') {
                isValid = false;
                validationErrors.push('company_name is empty');
                addLog('validation-log', formatTime(), 'FAILED', 'Condition B: company_name validation FAILED', 'error');
            } else {
                addLog('validation-log', formatTime(), 'PASSED', 'Condition B: company_name ✓', 'success');
            }

            if (!payload.title || payload.title.trim() === '') {
                isValid = false;
                validationErrors.push('job_title is empty');
                addLog('validation-log', formatTime(), 'FAILED', 'Condition C: job_title validation FAILED', 'error');
            } else {
                addLog('validation-log', formatTime(), 'PASSED', 'Condition C: job_title ✓', 'success');
            }

            // PHASE 2: Dual Routing
            await new Promise(r => setTimeout(r, 500));

            if (!isValid) {
                // PATH B: Invalid Data
                setNodeStatus('phase1-node', 'error');
                setNodeStatus('path-b-node1', 'processing');
                
                const timestamp2 = formatTime();
                addLog('execution-log', timestamp2, 'ROUTE', 'Routing to Path B: Fail-Safe', 'warning');
                
                await new Promise(r => setTimeout(r, 400));
                setNodeStatus('path-b-node1', 'success');
                setNodeStatus('path-b-node2', 'processing');

                const timestamp3 = formatTime();
                addLog('execution-log', timestamp3, 'FALLBACK', `Triggered fallback for: ${validationErrors.join(', ')}`, 'warning');
                
                await new Promise(r => setTimeout(r, 300));
                const timestamp4 = formatTime();
                
                const reviewEntry = `${timestamp4} | ${payloadId} | Status: REQUIRES_HUMAN_REVIEW | Reason: ${validationErrors.join('; ')}`;
                addLog('review-queue-log', timestamp4, 'QUEUED', reviewEntry, 'warning');

                setNodeStatus('path-b-node2', 'success');
                state.metrics.invalid++;
                state.metrics.humanReview++;
                
                document.getElementById('status-line').textContent = `⚠️ ${payloadId} flagged for human review`;
                updateMetrics();
                return;
            }

            // PATH A: Valid Data
            setNodeStatus('phase1-node', 'success');
            setNodeStatus('path-a-node1', 'processing');

            const timestamp2 = formatTime();
            addLog('execution-log', timestamp2, 'ROUTE', 'Routing to Path A: Execution', 'success');

            // Handle API Timeout
            if (testType === 'timeout') {
                await new Promise(r => setTimeout(r, 400));
                const timestamp3 = formatTime();
                addLog('execution-log', timestamp3, 'ENRICHMENT', 'Calling external enrichment API...', 'info');
                
                let retryCount = 0;
                for (let i = 0; i < 3; i++) {
                    await new Promise(r => setTimeout(r, 600));
                    const retryTime = formatTime();
                    
                    if (i < 2) {
                        addLog('execution-log', retryTime, 'RETRY', `Attempt ${i + 1}/2 - Timeout detected`, 'warning');
                    } else {
                        addLog('execution-log', retryTime, 'MAX_RETRIES', 'Enrichment API timeout - Max retries exceeded', 'error');
                        setNodeStatus('path-a-node1', 'error');
                        setNodeStatus('path-a-node2', 'processing');
                        
                        await new Promise(r => setTimeout(r, 300));
                        
                        // Reroute to Path B
                        setNodeStatus('path-b-node1', 'processing');
                        const timestamp4 = formatTime();
                        addLog('execution-log', timestamp4, 'FALLBACK', 'Enrichment timeout - Rerouting to Path B', 'warning');
                        
                        await new Promise(r => setTimeout(r, 300));
                        const timestamp5 = formatTime();
                        const reviewEntry = `${timestamp5} | ${payloadId} | Status: REQUIRES_HUMAN_REVIEW | Reason: Enrichment API Timeout (max retries exceeded)`;
                        addLog('review-queue-log', timestamp5, 'QUEUED', reviewEntry, 'warning');
                        
                        setNodeStatus('path-b-node2', 'success');
                        state.metrics.timeout++;
                        state.metrics.humanReview++;
                        
                        document.getElementById('status-line').textContent = `⏱️ ${payloadId} timeout - Fallback triggered`;
                        updateMetrics();
                        return;
                    }
                }
            }

            // Successful enrichment
            await new Promise(r => setTimeout(r, 500));
            const timestamp3 = formatTime();
            addLog('execution-log', timestamp3, 'ENRICHMENT', `✓ Enrichment complete for ${payload.company}`, 'success');

            const insights = [
                `Company Size: ${Math.floor(Math.random() * 5000) + 100} employees`,
                `Industry: ${['Technology', 'Finance', 'Healthcare', 'Retail'][Math.floor(Math.random() * 4)]}`,
                `Annual Revenue: $${Math.floor(Math.random() * 1000) + 10}M`
            ];

            insights.forEach((insight, idx) => {
                setTimeout(() => {
                    addLog('execution-log', formatTime(), 'INSIGHT', insight, 'success');
                }, idx * 200);
            });

            await new Promise(r => setTimeout(r, 800));
            setNodeStatus('path-a-node1', 'success');
            setNodeStatus('path-a-node2', 'processing');

            const timestamp4 = formatTime();
            addLog('execution-log', timestamp4, 'READY_TO_STORE', 'Clean data ready for database storage', 'success');

            await new Promise(r => setTimeout(r, 400));
            const timestamp5 = formatTime();

            const dbEntry = `${timestamp5} | ID: ${payloadId} | Email: ${payload.email} | Company: ${payload.company} | Title: ${payload.title} | Status: STORED`;
            addLog('database-log', timestamp5, 'INSERT', dbEntry, 'success');
            addLog('execution-log', timestamp5, 'SUCCESS', `Record inserted to database`, 'success');

            setNodeStatus('path-a-node2', 'success');

            state.metrics.valid++;
            state.metrics.database++;

            document.getElementById('status-line').textContent = `✓ ${payloadId} processed successfully (Path A)`;
            updateMetrics();
        }

        async function processClean() {
            const payload = {
                email: document.getElementById('lead-email').value || 'john.doe@acme.com',
                company: document.getElementById('company-name').value || 'Acme Corp',
                title: document.getElementById('job-title').value || 'Sales Director'
            };
            await processPayload(payload, 'normal');
        }

        async function processMissingEmail() {
            const payload = {
                email: '',
                company: 'TechCorp Inc',
                title: 'VP Sales'
            };
            await processPayload(payload, 'invalid-email');
        }

        async function processMissingCompany() {
            const payload = {
                email: 'jane@company.com',
                company: '',
                title: 'Marketing Manager'
            };
            await processPayload(payload, 'invalid-company');
        }

        async function processAPITimeout() {
            const payload = {
                email: 'test@company.com',
                company: 'DataFlow Systems',
                title: 'CTO'
            };
            await processPayload(payload, 'timeout');
        }

        function clearAll() {
            document.getElementById('validation-log').innerHTML = '';
            document.getElementById('execution-log').innerHTML = '';
            document.getElementById('database-log').innerHTML = '';
            document.getElementById('review-queue-log').innerHTML = '';

            state.metrics = {
                total: 0,
                valid: 0,
                invalid: 0,
                timeout: 0,
                humanReview: 0,
                database: 0
            };

            updateMetrics();

            document.querySelectorAll('.node, .path-a, .path-b').forEach(node => {
                node.classList.remove('processing', 'success', 'error', 'warning');
            });

            document.getElementById('status-line').textContent = 'System reset. Ready for payloads.';
        }

        // Initialize
        window.addEventListener('load', () => {
            updateMetrics();
            document.getElementById('status-line').textContent = 'Fail-Safe Gateway ready. Submit payloads.';
        });
    </script>
</body>
</html>
