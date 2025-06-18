<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Admin - Data Wali Santri</title>
  
  <!-- Appwrite Configuration -->
  <script src="appwrite-config.js"></script>
  
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      min-height: 100vh;
      background: linear-gradient(135deg, #22c55e 0%, #16a34a 50%, #15803d 100%);
      padding: 20px;
      color: #333;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      background: rgba(255, 255, 255, 0.95);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 40px;
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
      border: 1px solid rgba(255, 255, 255, 0.2);
    }

    h1 {
      color: #15803d;
      margin-bottom: 30px;
      font-size: 2.5rem;
      font-weight: 700;
      text-align: center;
      background: linear-gradient(135deg, #15803d, #16a34a);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .stats-section {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-bottom: 40px;
    }

    .stat-card {
      background: linear-gradient(135deg, #dcfce7 0%, #bbf7d0 100%);
      padding: 25px;
      border-radius: 15px;
      text-align: center;
      border: 2px solid rgba(34, 197, 94, 0.3);
      transition: transform 0.3s ease;
    }

    .stat-card:hover {
      transform: translateY(-5px);
    }

    .stat-number {
      font-size: 2.5rem;
      font-weight: 700;
      color: #15803d;
      display: block;
      margin-bottom: 10px;
    }

    .stat-label {
      color: #374151;
      font-weight: 600;
      font-size: 1.1rem;
    }

    .controls-section {
      display: flex;
      gap: 15px;
      margin-bottom: 30px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .btn {
      padding: 12px 24px;
      border: none;
      border-radius: 10px;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
      text-decoration: none;
      display: inline-block;
    }

    .btn-primary {
      background: linear-gradient(135deg, #16a34a, #15803d);
      color: white;
    }

    .btn-primary:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 20px rgba(22, 163, 74, 0.3);
    }

    .btn-secondary {
      background: linear-gradient(135deg, #6b7280, #4b5563);
      color: white;
    }

    .btn-secondary:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 20px rgba(107, 114, 128, 0.3);
    }

    .btn-success {
      background: linear-gradient(135deg, #10b981, #059669);
      color: white;
    }

    .btn-success:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 20px rgba(16, 185, 129, 0.3);
    }

    .search-section {
      margin-bottom: 30px;
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
    }

    .search-input {
      padding: 12px 20px;
      border: 2px solid #d1d5db;
      border-radius: 10px;
      font-size: 16px;
      min-width: 250px;
      transition: all 0.3s ease;
    }

    .search-input:focus {
      outline: none;
      border-color: #16a34a;
      box-shadow: 0 0 0 3px rgba(22, 163, 74, 0.1);
    }

    .filter-select {
      padding: 12px 20px;
      border: 2px solid #d1d5db;
      border-radius: 10px;
      font-size: 16px;
      background: white;
      cursor: pointer;
    }

    .data-table {
      width: 100%;
      border-collapse: collapse;
      background: white;
      border-radius: 15px;
      overflow: hidden;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    }

    .data-table th {
      background: linear-gradient(135deg, #15803d, #16a34a);
      color: white;
      padding: 15px;
      text-align: left;
      font-weight: 600;
      font-size: 14px;
    }

    .data-table td {
      padding: 15px;
      border-bottom: 1px solid #e5e7eb;
      font-size: 14px;
    }

    .data-table tr:hover {
      background: #f0fdf4;
    }

    .data-table tr:last-child td {
      border-bottom: none;
    }

    .no-data {
      text-align: center;
      padding: 60px 20px;
      color: #6b7280;
      font-size: 1.2rem;
    }

    .no-data-icon {
      font-size: 4rem;
      margin-bottom: 20px;
      display: block;
    }

    .export-section {
      margin-top: 30px;
      padding: 20px;
      background: linear-gradient(135deg, #f0fdf4 0%, #dcfce7 100%);
      border-radius: 15px;
      border: 2px solid rgba(34, 197, 94, 0.2);
    }

    .export-section h3 {
      color: #15803d;
      margin-bottom: 15px;
      font-size: 1.3rem;
    }

    .timestamp {
      color: #6b7280;
      font-size: 12px;
    }

    .user-type-badge {
      padding: 4px 8px;
      border-radius: 6px;
      font-size: 12px;
      font-weight: 600;
      text-transform: uppercase;
    }

    .user-type-undangan {
      background: #dbeafe;
      color: #1e3a8a;
    }

    .user-type-wali {
      background: #dcfce7;
      color: #166534;
    }

    @media (max-width: 768px) {
      .container {
        padding: 20px;
        margin: 10px;
      }
      
      h1 {
        font-size: 2rem;
      }
      
      .stats-section {
        grid-template-columns: 1fr;
      }
      
      .controls-section {
        flex-direction: column;
        align-items: center;
      }
      
      .search-section {
        flex-direction: column;
        align-items: center;
      }
      
      .search-input {
        min-width: 200px;
      }
      
      .data-table {
        font-size: 12px;
      }
      
      .data-table th,
      .data-table td {
        padding: 10px 8px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>📊 Dashboard Data Tamu</h1>

    <!-- Statistics Section -->
    <div class="stats-section">
      <div class="stat-card">
        <span id="totalTamu" class="stat-number">0</span>
        <div class="stat-label">Total Tamu</div>
      </div>
      <div class="stat-card">
        <span id="totalUndangan" class="stat-number">0</span>
        <div class="stat-label">Tamu Undangan</div>
      </div>
      <div class="stat-card">
        <span id="totalWali" class="stat-number">0</span>
        <div class="stat-label">Wali Santri</div>
      </div>
      <div class="stat-card">
        <span id="totalHariIni" class="stat-number">0</span>
        <div class="stat-label">Hari Ini</div>
      </div>
    </div>

    <!-- Controls Section -->
    <div class="controls-section">
      <button id="refreshBtn" class="btn btn-primary">🔄 Refresh Data</button>
      <button id="exportBtn" class="btn btn-success">📥 Export Excel</button>
      <button id="clearBtn" class="btn btn-secondary">🗑️ Clear Data</button>
    </div>

    <!-- Search Section -->
    <div class="search-section">
      <input type="text" id="searchInput" class="search-input" placeholder="Cari nama tamu atau santri..." />
      <select id="filterType" class="filter-select">
        <option value="">Semua Jenis</option>
        <option value="undangan">Tamu Undangan</option>
        <option value="wali_santri">Wali Santri</option>
      </select>
      <select id="filterDate" class="filter-select">
        <option value="">Semua Tanggal</option>
        <option value="today">Hari Ini</option>
        <option value="yesterday">Kemarin</option>
        <option value="week">Minggu Ini</option>
      </select>
    </div>

    <!-- Data Table -->
    <div class="table-container">
      <table id="dataTable" class="data-table">
        <thead>
          <tr>
            <th>No</th>
            <th>Waktu</th>
            <th>Jenis Tamu</th>
            <th>Nama Santri</th>
            <th>Kelas</th>
            <th>Device Info</th>
            <th>Aksi</th>
          </tr>
        </thead>
        <tbody id="tableBody">
          <tr>
            <td colspan="7" class="no-data">Memuat data...</td>
          </tr>
        </tbody>
      </table>
    </div>

    <!-- Status Section -->
    <div class="status-section" style="margin-top: 30px; text-align: center;">
      <div class="status-indicator">
        <span id="connectionStatus" class="status-dot">⏳</span>
        <span id="statusText">Menghubungkan ke server...</span>
      </div>
      <div class="last-update">
        <small>Update terakhir: <span id="lastUpdate">-</span></small>
      </div>
    </div>
  </div>

  <script>
    // Wait for DOM to be fully loaded
    document.addEventListener('DOMContentLoaded', function() {
      console.log('🚀 Admin dashboard loaded, initializing...');
      
      // Get DOM elements
      const totalTamu = document.getElementById('totalTamu');
      const totalUndangan = document.getElementById('totalUndangan');
      const totalWali = document.getElementById('totalWali');
      const totalHariIni = document.getElementById('totalHariIni');
      const refreshBtn = document.getElementById('refreshBtn');
      const exportBtn = document.getElementById('exportBtn');
      const clearBtn = document.getElementById('clearBtn');
      const searchInput = document.getElementById('searchInput');
      const filterType = document.getElementById('filterType');
      const filterDate = document.getElementById('filterDate');
      const tableBody = document.getElementById('tableBody');
      const connectionStatus = document.getElementById('connectionStatus');
      const statusText = document.getElementById('statusText');
      const lastUpdate = document.getElementById('lastUpdate');

      // Variables
      let allData = [];
      let filteredData = [];
      let realtimeSubscription = null;

      // Update status
      function updateStatus(message, isError = false) {
        if (statusText) {
          statusText.textContent = message;
        }
        if (connectionStatus) {
          connectionStatus.textContent = isError ? '❌' : '✅';
        }
      }

      // Update last update time
      function updateLastUpdateTime() {
        if (lastUpdate) {
          const now = new Date();
          lastUpdate.textContent = now.toLocaleTimeString('id-ID');
        }
      }

      // Initialize Appwrite
      async function initializeAppwrite() {
        try {
          console.log('🚀 Initializing Appwrite for admin...');
          updateStatus('Menghubungkan ke server...');
          
          // Initialize Appwrite service
          const success = await window.appwriteService.initialize();
          if (!success) {
            throw new Error('Failed to initialize Appwrite');
          }
          
          // Load initial data
          await loadData();
          
          // Setup real-time subscription
          setupRealtimeSubscription();
          
          updateStatus('Dashboard siap digunakan');
          console.log('✅ Admin Appwrite initialized successfully');
          
        } catch (error) {
          console.error('❌ Error initializing Appwrite:', error);
          updateStatus('Gagal terhubung ke server', true);
          
          // Fallback to localStorage
          console.log('🔄 Falling back to localStorage...');
          initializeLocalStorage();
        }
      }

      // Fallback to localStorage
      function initializeLocalStorage() {
        try {
          console.log('🔄 Initializing localStorage fallback for admin...');
          updateStatus('Menggunakan data lokal');
          
          loadLocalStorageData();
          
        } catch (error) {
          console.error('❌ Error initializing localStorage:', error);
          updateStatus('Gagal memuat data', true);
        }
      }

      // Load data from Appwrite
      async function loadData() {
        try {
          console.log('📊 Loading data from Appwrite...');
          
          const records = await window.appwriteService.getAttendanceRecords();
          allData = records.map(record => ({
            id: record.$id,
            user_id: record.user_id,
            user_type: record.user_type,
            timestamp: record.timestamp,
            device_info: record.device_info,
            student_name: record.student_name || '',
            student_class: record.student_class || '',
            created_at: record.$createdAt
          }));
          
          console.log('✅ Data loaded from Appwrite:', allData.length, 'records');
          
          // Update statistics
          updateStatistics();
          
          // Apply filters and render table
          applyFilters();
          
          updateLastUpdateTime();
          
        } catch (error) {
          console.error('❌ Error loading data:', error);
          updateStatus('Gagal memuat data', true);
        }
      }

      // Load data from localStorage (fallback)
      function loadLocalStorageData() {
        console.log('📊 Loading data from localStorage...');
        
        allData = [];
        const keys = Object.keys(localStorage);
        
        keys.forEach(key => {
          if (key.startsWith('attended_')) {
            try {
              const data = JSON.parse(localStorage.getItem(key));
              allData.push({
                id: key,
                user_id: data.user_id,
                user_type: data.user_type,
                timestamp: data.timestamp,
                device_info: data.device_info,
                student_name: data.student_name || '',
                student_class: data.student_class || '',
                created_at: data.timestamp
              });
            } catch (error) {
              console.error('❌ Error parsing localStorage data:', error);
            }
          }
        });
        
        console.log('✅ Data loaded from localStorage:', allData.length, 'records');
        
        // Update statistics
        updateStatistics();
        
        // Apply filters and render table
        applyFilters();
        
        updateLastUpdateTime();
      }

      // Update statistics
      function updateStatistics() {
        const total = allData.length;
        const undangan = allData.filter(item => item.user_type === 'undangan').length;
        const wali = allData.filter(item => item.user_type === 'wali_santri').length;
        const today = allData.filter(item => {
          const itemDate = new Date(item.timestamp);
          const today = new Date();
          return itemDate.toDateString() === today.toDateString();
        }).length;

        totalTamu.textContent = total;
        totalUndangan.textContent = undangan;
        totalWali.textContent = wali;
        totalHariIni.textContent = today;

        console.log('📈 Statistics updated:', { total, undangan, wali, today });
      }

      // Apply filters
      function applyFilters() {
        console.log('🔍 Applying filters...');
        
        let filtered = [...allData];
        
        // Search filter
        const searchTerm = searchInput.value.toLowerCase();
        if (searchTerm) {
          filtered = filtered.filter(item => 
            item.student_name.toLowerCase().includes(searchTerm) ||
            item.user_id.toLowerCase().includes(searchTerm)
          );
        }
        
        // Type filter
        const typeFilter = filterType.value;
        if (typeFilter) {
          filtered = filtered.filter(item => item.user_type === typeFilter);
        }
        
        // Date filter
        const dateFilter = filterDate.value;
        if (dateFilter) {
          const today = new Date();
          const yesterday = new Date(today);
          yesterday.setDate(yesterday.getDate() - 1);
          const weekAgo = new Date(today);
          weekAgo.setDate(weekAgo.getDate() - 7);
          
          filtered = filtered.filter(item => {
            const itemDate = new Date(item.timestamp);
            
            switch (dateFilter) {
              case 'today':
                return itemDate.toDateString() === today.toDateString();
              case 'yesterday':
                return itemDate.toDateString() === yesterday.toDateString();
              case 'week':
                return itemDate >= weekAgo;
              default:
                return true;
            }
          });
        }
        
        filteredData = filtered;
        renderTable();
        
        console.log('✅ Filters applied:', filteredData.length, 'records');
      }

      // Render table
      function renderTable() {
        console.log('📋 Rendering table...');
        
        if (filteredData.length === 0) {
          tableBody.innerHTML = '<tr><td colspan="7" class="no-data">Tidak ada data yang ditemukan</td></tr>';
          return;
        }
        
        const tableHTML = filteredData.map((item, index) => {
          const date = new Date(item.timestamp);
          const formattedDate = date.toLocaleString('id-ID');
          
          return `
            <tr>
              <td>${index + 1}</td>
              <td>${formattedDate}</td>
              <td>${item.user_type === 'undangan' ? 'Tamu Undangan' : 'Wali Santri'}</td>
              <td>${item.student_name || '-'}</td>
              <td>${item.student_class || '-'}</td>
              <td>${item.device_info.substring(0, 50)}...</td>
              <td>
                <button onclick="deleteRecord('${item.id}')" class="btn btn-secondary" style="padding: 5px 10px; font-size: 12px;">
                  🗑️
                </button>
              </td>
            </tr>
          `;
        }).join('');
        
        tableBody.innerHTML = tableHTML;
        console.log('✅ Table rendered successfully');
      }

      // Setup real-time subscription
      function setupRealtimeSubscription() {
        try {
          console.log('🔔 Setting up real-time subscription for admin...');
          
          realtimeSubscription = window.appwriteService.subscribeToAttendanceUpdates((response) => {
            console.log('📡 Real-time update received in admin:', response);
            
            // Reload data when new records are added or updated
            if (response.events.includes('databases.*.collections.*.documents.*.create') ||
                response.events.includes('databases.*.collections.*.documents.*.update') ||
                response.events.includes('databases.*.collections.*.documents.*.delete')) {
              loadData();
            }
          });
          
          console.log('✅ Real-time subscription set up successfully for admin');
          
        } catch (error) {
          console.error('❌ Error setting up real-time subscription:', error);
        }
      }

      // Delete record
      window.deleteRecord = async function(recordId) {
        if (!confirm('Apakah Anda yakin ingin menghapus data ini?')) {
          return;
        }
        
        try {
          console.log('🗑️ Deleting record:', recordId);
          
          if (window.appwriteService && window.appwriteService.isInitialized) {
            await window.appwriteService.databases.deleteDocument(
              window.appwriteService.config.databaseId,
              window.appwriteService.config.collectionId,
              recordId
            );
            console.log('✅ Record deleted from Appwrite');
          } else {
            // Fallback to localStorage
            localStorage.removeItem('attended_' + recordId);
            console.log('✅ Record deleted from localStorage');
          }
          
          // Reload data
          if (window.appwriteService && window.appwriteService.isInitialized) {
            await loadData();
          } else {
            loadLocalStorageData();
          }
          
        } catch (error) {
          console.error('❌ Error deleting record:', error);
          alert('Gagal menghapus data. Silakan coba lagi.');
        }
      };

      // Export to Excel
      function exportToExcel() {
        try {
          console.log('📥 Exporting data to Excel...');
          
          // Create CSV content
          const headers = ['No', 'Waktu', 'Jenis Tamu', 'Nama Santri', 'Kelas', 'Device Info'];
          const csvContent = [
            headers.join(','),
            ...filteredData.map((item, index) => {
              const date = new Date(item.timestamp);
              const formattedDate = date.toLocaleString('id-ID');
              const userType = item.user_type === 'undangan' ? 'Tamu Undangan' : 'Wali Santri';
              
              return [
                index + 1,
                formattedDate,
                userType,
                item.student_name || '',
                item.student_class || '',
                item.device_info
              ].join(',');
            })
          ].join('\n');
          
          // Create download link
          const blob = new Blob([csvContent], { type: 'text/csv;charset=utf-8;' });
          const link = document.createElement('a');
          const url = URL.createObjectURL(blob);
          link.setAttribute('href', url);
          link.setAttribute('download', `data_tamu_${new Date().toISOString().split('T')[0]}.csv`);
          link.style.visibility = 'hidden';
          document.body.appendChild(link);
          link.click();
          document.body.removeChild(link);
          
          console.log('✅ Data exported successfully');
          
        } catch (error) {
          console.error('❌ Error exporting data:', error);
          alert('Gagal mengexport data. Silakan coba lagi.');
        }
      }

      // Clear all data
      async function clearAllData() {
        if (!confirm('Apakah Anda yakin ingin menghapus semua data? Tindakan ini tidak dapat dibatalkan!')) {
          return;
        }
        
        try {
          console.log('🗑️ Clearing all data...');
          
          if (window.appwriteService && window.appwriteService.isInitialized) {
            // Get all records and delete them
            const records = await window.appwriteService.getAttendanceRecords();
            for (const record of records) {
              await window.appwriteService.databases.deleteDocument(
                window.appwriteService.config.databaseId,
                window.appwriteService.config.collectionId,
                record.$id
              );
            }
            console.log('✅ All data cleared from Appwrite');
          } else {
            // Clear localStorage
            const keys = Object.keys(localStorage);
            keys.forEach(key => {
              if (key.startsWith('attended_')) {
                localStorage.removeItem(key);
              }
            });
            console.log('✅ All data cleared from localStorage');
          }
          
          // Reload data
          if (window.appwriteService && window.appwriteService.isInitialized) {
            await loadData();
          } else {
            loadLocalStorageData();
          }
          
          alert('Semua data berhasil dihapus!');
          
        } catch (error) {
          console.error('❌ Error clearing data:', error);
          alert('Gagal menghapus data. Silakan coba lagi.');
        }
      }

      // Event listeners
      refreshBtn.addEventListener('click', async function() {
        console.log('🔄 Refresh button clicked');
        if (window.appwriteService && window.appwriteService.isInitialized) {
          await loadData();
        } else {
          loadLocalStorageData();
        }
      });

      exportBtn.addEventListener('click', function() {
        console.log('📥 Export button clicked');
        exportToExcel();
      });

      clearBtn.addEventListener('click', function() {
        console.log('🗑️ Clear button clicked');
        clearAllData();
      });

      searchInput.addEventListener('input', function() {
        console.log('🔍 Search input changed');
        applyFilters();
      });

      filterType.addEventListener('change', function() {
        console.log('🔍 Type filter changed');
        applyFilters();
      });

      filterDate.addEventListener('change', function() {
        console.log('🔍 Date filter changed');
        applyFilters();
      });

      // Initialize application
      initializeAppwrite();
      
      console.log('🎉 Admin dashboard initialized successfully!');
    });
  </script>
</body>
</html> 
