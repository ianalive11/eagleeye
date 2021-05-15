<template>
  <el-container class="bg">
    <el-header class="header" style="height: 59px">
      <div class="header-left">
        <div class="hamburger">
          <svg width="18" height="12" viewBox="0 0 18 12" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M0 12H18V10H0V12ZM0 7H18V5H0V7ZM0 0V2H18V0H0Z" fill="white"/>
          </svg>
        </div>
        <div class="logo"><svg width="170" height="24" viewBox="0 0 170 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M109.547 15.181L109.061 18.073H102.623C101.556 18.1029 100.49 17.9903 99.453 17.738C98.7796 17.5865 98.1723 17.2234 97.72 16.702C97.3331 16.1795 97.1229 15.5472 97.12 14.897C97.1048 14.0051 97.1843 13.1141 97.357 12.239C97.5082 11.3516 97.745 10.4808 98.064 9.63901C98.3287 8.93354 98.7555 8.30017 99.31 7.79001C99.9235 7.25967 100.654 6.88265 101.442 6.69001C102.54 6.42645 103.667 6.30579 104.795 6.33101C105.852 6.30241 106.907 6.41507 107.934 6.66601C108.602 6.82072 109.209 7.17218 109.675 7.67501C110.067 8.16024 110.292 8.75941 110.316 9.38301C110.356 10.1904 110.295 10.9996 110.136 11.792L109.869 13.25H100.791C100.739 13.5612 100.739 13.8789 100.791 14.19C100.84 14.426 100.973 14.6361 101.166 14.781C101.41 14.9472 101.689 15.054 101.981 15.093C102.42 15.1565 102.863 15.1852 103.307 15.179H109.551L109.547 15.181ZM104.447 9.00001C103.986 8.99436 103.526 9.02377 103.07 9.08801C102.737 9.12876 102.414 9.23369 102.121 9.39701C101.873 9.54187 101.668 9.75085 101.529 10.002C101.37 10.2997 101.262 10.6218 101.209 10.955L101.184 11.101H106.75L106.777 10.955C106.846 10.6421 106.858 10.3194 106.814 10.002C106.781 9.76478 106.657 9.54972 106.468 9.40201C106.236 9.23676 105.967 9.13069 105.685 9.09301C105.275 9.02654 104.86 8.99542 104.445 9.00001H104.447Z" fill="white"/>
          <path d="M80.145 15.181L79.645 18.073H73.263C72.1964 18.103 71.1307 17.9903 70.094 17.738C69.4194 17.5864 68.8109 17.2235 68.357 16.702C67.9703 16.1793 67.7602 15.5471 67.757 14.897C67.74 14.0049 67.8205 13.1136 67.997 12.239C68.1469 11.3514 68.3834 10.4805 68.703 9.63897C68.9697 8.93186 69.3981 8.29695 69.954 7.78497C70.568 7.256 71.2981 6.87916 72.085 6.68497C73.1836 6.42161 74.3115 6.30095 75.441 6.32597C76.4972 6.29748 77.5526 6.41014 78.579 6.66097C79.2463 6.8178 79.8513 7.17099 80.316 7.67497C80.7078 8.16052 80.9326 8.75951 80.957 9.38297C80.9956 10.1904 80.9345 10.9995 80.775 11.792L80.51 13.252H71.433C71.38 13.5631 71.38 13.8809 71.433 14.192C71.4805 14.4286 71.6141 14.6392 71.808 14.783C72.0519 14.9493 72.3313 15.0562 72.624 15.095C73.0627 15.1585 73.5057 15.1872 73.949 15.181H80.145ZM75.092 8.99997C74.6301 8.99421 74.1684 9.02363 73.711 9.08797C73.3777 9.12872 73.0554 9.23365 72.762 9.39697C72.5145 9.54289 72.3099 9.75159 72.169 10.002C72.0121 10.3003 71.9047 10.6222 71.851 10.955L71.824 11.101H77.391L77.417 10.955C77.4846 10.6419 77.4981 10.3196 77.457 10.002C77.422 9.76482 77.2975 9.55009 77.109 9.40197C76.8773 9.23691 76.6089 9.13085 76.327 9.09297C75.9187 9.02684 75.5055 8.99573 75.092 8.99997Z" fill="white"/>
          <path d="M82.456 20.175C82.816 20.1791 83.1758 20.1547 83.532 20.102C83.8333 20.0568 84.1269 19.9697 84.404 19.843C84.6877 19.7125 84.947 19.5346 85.171 19.317C85.4519 19.0412 85.6999 18.7339 85.91 18.401L82.39 6.73999H86.484L88.484 14.328L93.236 6.73999H97.285L88.857 19.631C88.4739 20.226 88.0435 20.7891 87.57 21.315C87.1549 21.7705 86.6694 22.1564 86.132 22.458C85.5645 22.7647 84.9524 22.9803 84.318 23.097C83.5164 23.2394 82.7031 23.3063 81.889 23.297H80.526L82.188 20.175H82.456Z" fill="white"/>
          <path d="M14.785 11.1461H5.42L4.836 14.3641H14.284L13.61 18.0751H0L3.119 0.904053H16.686L16.01 4.61505H6.61L6.022 7.83505H15.386L14.785 11.1461Z" fill="white"/>
          <path d="M17.751 9.49602L18.27 6.62802H23.801C24.7943 6.6082 25.7868 6.69943 26.76 6.90002C27.4213 7.02531 28.0403 7.31523 28.56 7.74302C28.9812 8.11486 29.2613 8.62064 29.353 9.17502C29.4553 9.8649 29.4343 10.5675 29.291 11.25L28.051 18.075H19.873C19.2856 18.0923 18.699 18.0208 18.133 17.863C17.7386 17.7565 17.3858 17.5331 17.121 17.222C16.8765 16.8971 16.7405 16.5035 16.732 16.097C16.7105 15.5414 16.7548 14.9852 16.864 14.44C16.9529 13.8927 17.1066 13.358 17.322 12.847C17.4931 12.4494 17.7605 12.1006 18.1 11.832C18.4643 11.5619 18.884 11.3761 19.329 11.288C19.9238 11.1727 20.5291 11.1201 21.135 11.131H25.71L25.728 11.031C25.7753 10.8035 25.7798 10.5691 25.741 10.34C25.7219 10.2406 25.6822 10.1463 25.6245 10.0631C25.5668 9.97992 25.4924 9.90973 25.406 9.85702C25.1523 9.71302 24.8725 9.6209 24.583 9.58602C24.0991 9.52066 23.6111 9.49158 23.123 9.49902L17.751 9.49602ZM24.927 15.452L25.313 13.327H21.56C21.2646 13.2999 20.9693 13.379 20.727 13.55C20.5239 13.7661 20.3986 14.0438 20.371 14.339C20.282 14.625 20.302 14.9338 20.427 15.206C20.5383 15.37 20.7873 15.452 21.174 15.452H24.927Z" fill="white"/>
          <path d="M48.5871 0H52.6101L49.3271 18.075H45.3051L48.5871 0Z" fill="white"/>
          <path d="M64.8609 15.181L64.335 18.075H57.9819C56.9144 18.1049 55.8477 17.9922 54.81 17.74C54.1366 17.5875 53.5293 17.2246 53.0759 16.704C52.688 16.182 52.4777 15.5493 52.476 14.899C52.4572 14.0069 52.537 13.1155 52.7139 12.241C52.8637 11.3532 53.1005 10.4824 53.421 9.64099C53.688 8.93432 54.116 8.29955 54.671 7.78699C55.2859 7.25761 56.017 6.88073 56.8049 6.68699C57.9025 6.42361 59.0295 6.30295 60.1579 6.32799C61.2142 6.29926 62.2696 6.41193 63.296 6.66299C63.9635 6.81874 64.569 7.17128 65.0339 7.67499C65.4254 8.16067 65.6499 8.75964 65.6739 9.38299C65.7134 10.1903 65.6529 10.9995 65.4939 11.792L65.2289 13.25H56.15C56.097 13.5611 56.097 13.8789 56.15 14.19C56.1959 14.4267 56.329 14.6376 56.5229 14.781C56.7666 14.9477 57.0462 15.0546 57.3389 15.093C57.7777 15.1564 58.2207 15.1852 58.664 15.179H64.864L64.8609 15.181ZM59.81 8.99999C59.3477 8.99422 58.8857 9.02363 58.428 9.08799C58.0947 9.12913 57.7725 9.23404 57.4789 9.39699C57.2309 9.54185 57.0264 9.75083 56.887 10.002C56.7293 10.3001 56.6215 10.622 56.5679 10.955L56.5419 11.101H62.11L62.136 10.955C62.2035 10.6419 62.2164 10.3195 62.1739 10.002C62.1395 9.76466 62.0148 9.54977 61.8259 9.40199C61.5938 9.2371 61.3251 9.13106 61.0429 9.09299C60.6354 9.02677 60.2229 8.99565 59.81 8.99999Z" fill="white"/>
          <path d="M44.1029 8.90501C44.1798 8.64488 44.196 8.3706 44.1503 8.10322C44.1047 7.83585 43.9983 7.5825 43.8395 7.36263C43.6806 7.14276 43.4735 6.96222 43.234 6.83487C42.9945 6.70753 42.729 6.63676 42.4579 6.62801H37.7289C36.7813 6.61289 35.8352 6.70888 34.9099 6.91401C34.1896 7.07283 33.5168 7.39896 32.9459 7.86601C32.3936 8.34749 31.9565 8.94692 31.6669 9.62001C31.3031 10.4756 31.0429 11.3716 30.8919 12.289C30.7128 13.1622 30.6489 14.0552 30.7019 14.945C30.7322 15.5746 30.9576 16.1793 31.3469 16.675C31.7758 17.1496 32.3428 17.4776 32.9679 17.613C33.8582 17.8249 34.7721 17.9214 35.6869 17.9H38.6779L38.5389 18.666C38.5113 18.8951 38.4344 19.1155 38.3136 19.3121C38.1928 19.5087 38.0309 19.6769 37.8389 19.805C37.3152 20.0702 36.7297 20.1897 36.1439 20.151H31.6749L30.0179 23.294H35.5479C36.5012 23.3071 37.4534 23.224 38.3899 23.046C39.0973 22.9135 39.7719 22.6441 40.3759 22.253C40.907 21.8959 41.3411 21.4124 41.6389 20.846C41.9759 20.1762 42.2076 19.4584 42.3259 18.718L44.1099 8.90201L44.1029 8.90501ZM39.2329 14.81H36.1749C35.8648 14.8194 35.5552 14.7771 35.2589 14.685C35.0387 14.6172 34.8502 14.4724 34.7279 14.277C34.6048 14.046 34.5448 13.7866 34.5539 13.525C34.5578 13.1358 34.598 12.7478 34.6739 12.366C34.7484 11.6643 35.0125 10.996 35.4379 10.433C35.658 10.2355 35.9164 10.0854 36.197 9.99212C36.4776 9.89886 36.7744 9.86445 37.0689 9.89101H40.1239L39.2329 14.81Z" fill="white"/>
          <path d="M138.232 13.418L137.673 16.586C135.824 17.5162 133.786 18.0098 131.716 18.029C129.14 18.029 127.214 17.3177 125.939 15.895C125.309 15.1902 124.857 14.3449 124.62 13.4297C124.383 12.5145 124.369 11.5559 124.578 10.634C124.974 8.50103 126.173 6.60118 127.928 5.32602C129.846 3.85421 132.211 3.08411 134.628 3.14402C136.394 3.06366 138.144 3.50801 139.657 4.42102L139.089 7.65102C137.684 6.71619 136.042 6.20107 134.355 6.16602C132.92 6.1319 131.513 6.56769 130.349 7.40702C129.819 7.77423 129.367 8.24283 129.019 8.78574C128.672 9.32864 128.435 9.93509 128.323 10.57C128.191 11.1331 128.203 11.7205 128.358 12.2778C128.513 12.8351 128.806 13.3442 129.21 13.758C129.675 14.1962 130.224 14.534 130.825 14.7505C131.426 14.9669 132.065 15.0573 132.702 15.016C133.45 15.0141 134.194 14.9132 134.915 14.716C136.05 14.3635 137.159 13.9298 138.232 13.418Z" fill="white"/>
          <path d="M142.336 3.33301H148.736C151.207 3.33301 153.04 4.01001 154.236 5.36401C154.84 6.08043 155.266 6.92937 155.48 7.84168C155.694 8.75399 155.689 9.70388 155.466 10.614C155.155 12.7194 154.035 14.6206 152.345 15.914C150.428 17.2705 148.113 17.9489 145.767 17.842H139.775L142.336 3.33301ZM145.48 5.99301L143.859 15.185H146.218C147.576 15.2446 148.907 14.794 149.949 13.922C150.92 13.057 151.557 11.879 151.749 10.593C151.9 10.0193 151.922 9.41902 151.812 8.83599C151.701 8.25297 151.462 7.70191 151.112 7.22301C150.687 6.78106 150.168 6.4408 149.593 6.22765C149.018 6.01449 148.402 5.93394 147.792 5.99201H145.48V5.99301Z" fill="white"/>
          <path d="M159.025 3.33306H165.496C166.103 3.28543 166.713 3.37564 167.28 3.59695C167.847 3.81826 168.357 4.16494 168.771 4.61106C169.122 5.02236 169.373 5.5088 169.506 6.0328C169.639 6.5568 169.649 7.10433 169.537 7.63306C169.318 8.85175 168.669 9.95158 167.709 10.7331C166.668 11.604 165.343 12.0624 163.986 12.0211H161.11L160.083 17.8471H156.47L159.025 3.33306ZM162.17 5.99306L161.576 9.35806H163.26C164.762 9.35806 165.612 8.79706 165.811 7.67506C165.89 7.44442 165.897 7.19525 165.83 6.9607C165.764 6.72615 165.628 6.51734 165.44 6.36206C164.823 6.05996 164.135 5.93236 163.451 5.99306H162.17Z" fill="white"/>
          <path d="M118.498 14.1129C119.554 14.1129 120.41 13.2569 120.41 12.2009C120.41 11.145 119.554 10.2889 118.498 10.2889C117.442 10.2889 116.586 11.145 116.586 12.2009C116.586 13.2569 117.442 14.1129 118.498 14.1129Z" fill="white"/>
          </svg>
        </div>
      </div>
      <div class="acct">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M12 12C12.7911 12 13.5645 11.7654 14.2223 11.3259C14.8801 10.8864 15.3928 10.2616 15.6955 9.53074C15.9983 8.79983 16.0775 7.99556 15.9231 7.21964C15.7688 6.44372 15.3878 5.73098 14.8284 5.17157C14.269 4.61216 13.5563 4.2312 12.7804 4.07686C12.0044 3.92252 11.2002 4.00173 10.4693 4.30448C9.73836 4.60723 9.11365 5.11992 8.67412 5.77772C8.2346 6.43552 8 7.20888 8 8C8 9.06087 8.42143 10.0783 9.17157 10.8284C9.92172 11.5786 10.9391 12 12 12ZM12 14C9.33 14 4 15.34 4 18V20H20V18C20 15.34 14.67 14 12 14Z" fill="white"/>
        </svg>
      </div>
    </el-header>
    <el-main class="main-wrap">
      <!-- 麵包屑 -->
      <el-breadcrumb separator-class="el-icon-arrow-right">
        <el-breadcrumb-item>首页</el-breadcrumb-item>
        <el-breadcrumb-item :to="{ path: '/' }">智慧名單</el-breadcrumb-item>
      </el-breadcrumb>
      <h1>智慧名單</h1>
      <el-tabs type="card">
        <!-- 全部 -->
        <el-tab-pane label="全部">
          <div class="table-bg">
            <div class="updateTime">資料更新時間： 2021-02-23 11:36:01</div>
            <h2>拉新</h2><hr>
            <el-table class="table-color" :data="create" stripe style="width: 100%" :default-sort = "{prop: 'date', order: 'descending'}">
              <el-table-column prop="name" label="名稱" > </el-table-column>
              <el-table-column prop="content" label="描述"> </el-table-column>
              <el-table-column prop="num" label="受眾人數" sortable></el-table-column>
              <el-table-column prop="date" label="更新日期" sortable></el-table-column>
              <el-table-column prop="hover" label="操作" width="100">
                <template slot-scope="scope">
                  <el-dropdown>
                      <span class="el-dropdown-link">
                          更多<i class="el-icon-arrow-down el-icon--right"></i>
                      </span>
                      <el-dropdown-menu slot="dropdown">
                          <el-dropdown-item>下載</el-dropdown-item>
                          <el-dropdown-item>複製連結</el-dropdown-item>
                          <el-dropdown-item>新增SMS行銷</el-dropdown-item>
                      </el-dropdown-menu>
                  </el-dropdown>
                </template>
              </el-table-column>
            </el-table>
            <h2>留存</h2><hr>
            <el-table class="table-color" :data="save" stripe style="width: 100%" :default-sort = "{prop: 'date', order: 'descending'}">
              <el-table-column prop="name" label="名稱"> </el-table-column>
              <el-table-column prop="content" label="描述"> </el-table-column>
              <el-table-column prop="num" label="受眾人數" sortable></el-table-column>
              <el-table-column prop="date" label="更新日期" sortable></el-table-column>
              <el-table-column prop="hover" label="操作" width="100">
                <template slot-scope="scope">
                  <el-dropdown>
                      <span class="el-dropdown-link">
                          更多<i class="el-icon-arrow-down el-icon--right"></i>
                      </span>
                      <el-dropdown-menu slot="dropdown">
                          <el-dropdown-item>下載</el-dropdown-item>
                          <el-dropdown-item>複製連結</el-dropdown-item>
                          <el-dropdown-item>新增SMS行銷</el-dropdown-item>
                      </el-dropdown-menu>
                  </el-dropdown>
                </template>
              </el-table-column>
            </el-table>
            <h2>促活</h2><hr>
            <el-table class="table-color" :data="promote" stripe style="width: 100%" :default-sort = "{prop: 'date', order: 'descending'}">
              <el-table-column prop="name" label="名稱"> </el-table-column>
              <el-table-column prop="content" label="描述"> </el-table-column>
              <el-table-column prop="num" label="受眾人數" sortable></el-table-column>
              <el-table-column prop="date" label="更新日期" sortable></el-table-column>
              <el-table-column prop="hover" label="操作" width="100">
                <template slot-scope="scope">
                  <el-dropdown>
                      <span class="el-dropdown-link">
                          更多<i class="el-icon-arrow-down el-icon--right"></i>
                      </span>
                      <el-dropdown-menu slot="dropdown">
                          <el-dropdown-item>下載</el-dropdown-item>
                          <el-dropdown-item>複製連結</el-dropdown-item>
                          <el-dropdown-item>新增SMS行銷</el-dropdown-item>
                      </el-dropdown-menu>
                  </el-dropdown>
                </template>
              </el-table-column>
            </el-table>
          </div>
        </el-tab-pane>
        <!-- 拉新(拓展客戶) -->
        <el-tab-pane label="拉新(拓展新客)">
          <div class="table-bg">
            <h2>拉新</h2><hr>
            <el-table class="table-color" :data="create" stripe style="width: 100%" :default-sort = "{prop: 'date', order: 'descending'}">
              <el-table-column prop="name" label="名稱"> </el-table-column>
              <el-table-column prop="content" label="描述"> </el-table-column>
              <el-table-column prop="num" label="受眾人數" sortable></el-table-column>
              <el-table-column prop="date" label="更新日期" sortable></el-table-column>
              <el-table-column prop="hover" label="操作" width="100">
                <template slot-scope="scope">
                  <el-dropdown>
                      <span class="el-dropdown-link">
                          更多<i class="el-icon-arrow-down el-icon--right"></i>
                      </span>
                      <el-dropdown-menu slot="dropdown">
                          <el-dropdown-item>下載</el-dropdown-item>
                          <el-dropdown-item>複製連結</el-dropdown-item>
                          <el-dropdown-item>新增SMS行銷</el-dropdown-item>
                      </el-dropdown-menu>
                  </el-dropdown>
                </template>
              </el-table-column>
            </el-table>
          </div>
        </el-tab-pane>
        <!-- 留存(避免流失) -->
        <el-tab-pane label="留存(避免流失)">
          <div class="table-bg">
          <h2>留存</h2><hr>
            <el-table class="table-color" :data="save" stripe style="width: 100%" :default-sort = "{prop: 'date', order: 'descending'}">
              <el-table-column prop="name" label="名稱"> </el-table-column>
              <el-table-column prop="content" label="描述"> </el-table-column>
              <el-table-column prop="num" label="受眾人數" sortable></el-table-column>
              <el-table-column prop="date" label="更新日期" sortable></el-table-column>
              <el-table-column prop="hover" label="操作" width="100">
                <template slot-scope="scope">
                  <el-dropdown>
                      <span class="el-dropdown-link">
                          更多<i class="el-icon-arrow-down el-icon--right"></i>
                      </span>
                      <el-dropdown-menu slot="dropdown">
                          <el-dropdown-item>下載</el-dropdown-item>
                          <el-dropdown-item>複製連結</el-dropdown-item>
                          <el-dropdown-item>新增SMS行銷</el-dropdown-item>
                      </el-dropdown-menu>
                  </el-dropdown>
                </template>
              </el-table-column>
            </el-table>
          </div>
        </el-tab-pane>
        <!-- 促活(促進活躍) -->
        <el-tab-pane label="促活(促進活躍)">
          <div class="table-bg">
            <h2>促活</h2><hr>
            <el-table class="table-color" :data="promote" stripe style="width: 100%">
              <el-table-column prop="name" label="名稱"> </el-table-column>
              <el-table-column prop="content" label="描述"> </el-table-column>
              <el-table-column prop="num" label="受眾人數" sortable></el-table-column>
              <el-table-column prop="date" label="更新日期" sortable></el-table-column>
              <el-table-column prop="hover" label="操作" width="100">
                <template slot-scope="scope">
                  <el-dropdown>
                      <span class="el-dropdown-link">
                          更多<i class="el-icon-arrow-down el-icon--right"></i>
                      </span>
                      <el-dropdown-menu slot="dropdown">
                          <el-dropdown-item>下載</el-dropdown-item>
                          <el-dropdown-item>複製連結</el-dropdown-item>
                          <el-dropdown-item>新增SMS行銷</el-dropdown-item>
                      </el-dropdown-menu>
                  </el-dropdown>
                </template>
              </el-table-column>
            </el-table>
          </div>
        </el-tab-pane>
      </el-tabs>
    </el-main>
    <el-footer class="footer" style="height: 59px">紅門互動股份有限公司 © 2021 REDDOOR MEDIA</el-footer>
  </el-container>
</template>

<script>
import '@/scss/style.scss'
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
    data() {
      return {
        create: [{
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        },{
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        },{
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        }],
        save: [{
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        },{
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        },{
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        }],
        promote: [{
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        },{
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        },{
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47,
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        }, {
          date: '2020-03-21',
          name: '忠實老會員(VVIP)',
          content: '經常消費且購買金額高的忠實會員',
          num: 47
        }]
      }
    },
     methods: {
      formatter(row) {
        return row.content;
      }
    }
}
</script>
