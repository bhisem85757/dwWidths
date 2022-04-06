# dwWidths
g_DXGIManager.SetCaptureSource(CSDesktop);    RECT rcDim;   g_DXGIManager.GetOutputRect(rcDim);    DWORD dwWidth = rcDim.right - rcDim.left;   DWORD dwHeight = rcDim.bottom - rcDim.top;    printf("dwWidth=%d dwHeight=%d\n", dwWidth, dwHeight);    DWORD dwBufSize = dwWidth*dwHeight * 4;
