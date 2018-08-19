RAGE Plugin Hook v0.63.1224.15140 PUBLIC ALPHA

Game: Grand Theft Auto V
Game build: 1493
Branch: Retail

Plugins loaded at the time of the crash:

No plugin was ticking at the time of this crash.
Base address: 00007ff62bda0000
Exception address: 00007ff62c9e8a20
Exception offset: 00c48a20
Exception code: 0xc0000005 (EXCEPTION_ACCESS_VIOLATION)

Stack trace (unmanaged):
	0x00007ffab79fc0a0 - UnhandledExceptionFilter - in Unknown:0 (C:\WINDOWS\System32\KERNELBASE.dll)
	0x00007ffabb1426d7 - memset - in Unknown:0 (C:\WINDOWS\SYSTEM32\ntdll.dll)
	0x00007ffabb12ab06 - _C_specific_handler - in Unknown:0 (C:\WINDOWS\SYSTEM32\ntdll.dll)
	0x00007ffabb13eced - _chkstk - in Unknown:0 (C:\WINDOWS\SYSTEM32\ntdll.dll)
	0x00007ffabb0a6c86 - RtlWalkFrameChain - in Unknown:0 (C:\WINDOWS\SYSTEM32\ntdll.dll)
	0x00007ffabb13dc1e - KiUserExceptionDispatcher - in Unknown:0 (C:\WINDOWS\SYSTEM32\ntdll.dll)
	0x00007ff62c9e8a20 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62d04fbba - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62d0555fe - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62d050210 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62d050299 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62c9e54f8 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62c9e0de1 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62c9e0ef3 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62d3040ee - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62bdb4299 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62bdb6ac0 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62bdb65d6 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62bdc567b - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62bdbee37 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62d308cd0 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62bda14a8 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62d011037 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ff62d4fa9a8 - KiUserExceptionDispatcher - in Unknown:0 (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	0x00007ffaba743034 - BaseThreadInitThunk - in Unknown:0 (C:\WINDOWS\System32\KERNEL32.DLL)
	0x00007ffabb111431 - RtlUserThreadStart - in Unknown:0 (C:\WINDOWS\SYSTEM32\ntdll.dll)

Stack trace (managed):
	  Hook:OnGameCrashManaged(_EXCEPTION_POINTERS* exceptionInfo, Void** stackFrames, Int32 framesCaptured, SByte* exceptionName, Plugin plugin, String pluginStackTrace)
	  Hook:OnGameCrashManaged(_EXCEPTION_POINTERS* exceptionInfo, Void** stackFrames, Int32 framesCaptured, SByte* exceptionName)


General purpose registers:
	RAX: 0x000001ba1429c7e0
	RCX: 0x0000000000000000
	RDX: 0x0000000000000010
	RBX: 0x000000009c03f8aa
	RSP: 0x000000b73b4ff8e0
	RBP: 0x00000000000000e8
	RSI: 0x00000000000000e8
	RDI: 0x000001ba142a4220
	R8: 0x000000000000000c
	R9: 0x000001ba13d8e280
	R10: 0x00007ff62dc07860
	R11: 0x00007ff62d79b090
	R12: 0xffffffffffffffff
	R13: 0x000001ba0014a4d0
	R14: 0x0000000000000000
	R15: 0x0000000000000000
	RIP: 0x00007ff62c9e8a20

Segment registers:
	CS: 0x0033
	DS: 0x002b
	ES: 0x002b
	FS: 0x0053
	GS: 0x002b
	SS: 0x002b
	Flags: 0x00010297

Debug registers:
	Dr0: 0x0000000000000000
	Dr1: 0x0000000000000000
	Dr2: 0x0000000000000000
	Dr3: 0x0000000000000000
	Dr6: 0x0000000000000000
	Dr7: 0x0000000000000000

Floating point state:
	Xmm0: Low: 0x3fc99999a0000000, High: 0x3fc99999a0000000
	Xmm1: Low: 0x000000003e4ccccd, High: 0x000000003e4ccccd
	Xmm2: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm3: Low: 0x2e2e2e2e2e2e2e2e, High: 0x2e2e2e2e2e2e2e2e
	Xmm4: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm5: Low: 0x03020100ffffffff, High: 0x03020100ffffffff
	Xmm6: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm7: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm8: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm9: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm10: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm11: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm12: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm13: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm14: Low: 0x0000000000000000, High: 0x0000000000000000
	Xmm15: Low: 0x0000000000000000, High: 0x0000000000000000

Threads:
	Id: 8408 (0x20d8) (CURRENT); state: Running
	Id: 14404 (0x3844)state: Wait (Reason: EventPairLow)
	Id: 13160 (0x3368)state: Wait (Reason: EventPairLow)
	Id: 8332 (0x208c)state: Wait (Reason: EventPairLow)
	Id: 2836 (0x0b14)state: Wait (Reason: EventPairLow)
	Id: 8420 (0x20e4)state: Wait (Reason: EventPairLow)
	Id: 15316 (0x3bd4)state: Wait (Reason: UserRequest)
	Id: 2092 (0x082c)state: Wait (Reason: ExecutionDelay)
	Id: 1720 (0x06b8)state: Wait (Reason: UserRequest)
	Id: 3056 (0x0bf0)state: Wait (Reason: UserRequest)
	Id: 12896 (0x3260)state: Wait (Reason: UserRequest)
	Id: 7496 (0x1d48)state: Wait (Reason: ExecutionDelay)
	Id: 15236 (0x3b84)state: Wait (Reason: UserRequest)
	Id: 13832 (0x3608)state: Wait (Reason: UserRequest)
	Id: 6292 (0x1894)state: Wait (Reason: UserRequest)
	Id: 15040 (0x3ac0)state: Wait (Reason: UserRequest)
	Id: 12644 (0x3164)state: Wait (Reason: UserRequest)
	Id: 7308 (0x1c8c)state: Wait (Reason: UserRequest)
	Id: 14676 (0x3954)state: Running
	Id: 13008 (0x32d0)state: Ready
	Id: 11520 (0x2d00)state: Wait (Reason: UserRequest)
	Id: 8600 (0x2198)state: Wait (Reason: UserRequest)
	Id: 7104 (0x1bc0)state: Wait (Reason: UserRequest)
	Id: 2740 (0x0ab4)state: Wait (Reason: UserRequest)
	Id: 5704 (0x1648)state: Wait (Reason: UserRequest)
	Id: 10996 (0x2af4)state: Wait (Reason: UserRequest)
	Id: 1696 (0x06a0)state: Wait (Reason: UserRequest)
	Id: 10568 (0x2948)state: Wait (Reason: UserRequest)
	Id: 8052 (0x1f74)state: Wait (Reason: UserRequest)
	Id: 10136 (0x2798)state: Ready
	Id: 11108 (0x2b64)state: Wait (Reason: EventPairLow)
	Id: 3960 (0x0f78)state: Wait (Reason: UserRequest)
	Id: 14732 (0x398c)state: Wait (Reason: UserRequest)
	Id: 4616 (0x1208)state: Wait (Reason: ExecutionDelay)
	Id: 14592 (0x3900)state: Wait (Reason: UserRequest)
	Id: 11304 (0x2c28)state: Wait (Reason: UserRequest)
	Id: 3548 (0x0ddc)state: Wait (Reason: UserRequest)
	Id: 13484 (0x34ac)state: Wait (Reason: UserRequest)
	Id: 11124 (0x2b74)state: Wait (Reason: UserRequest)
	Id: 14488 (0x3898)state: Wait (Reason: UserRequest)
	Id: 4588 (0x11ec)state: Ready
	Id: 8024 (0x1f58)state: Wait (Reason: UserRequest)
	Id: 14844 (0x39fc)state: Wait (Reason: UserRequest)
	Id: 5160 (0x1428)state: Wait (Reason: EventPairLow)
	Id: 8404 (0x20d4)state: Wait (Reason: UserRequest)
	Id: 11796 (0x2e14)state: Wait (Reason: UserRequest)
	Id: 3808 (0x0ee0)state: Wait (Reason: UserRequest)
	Id: 11492 (0x2ce4)state: Wait (Reason: UserRequest)
	Id: 4752 (0x1290)state: Wait (Reason: UserRequest)
	Id: 6216 (0x1848)state: Wait (Reason: UserRequest)
	Id: 12976 (0x32b0)state: Wait (Reason: UserRequest)
	Id: 13624 (0x3538)state: Wait (Reason: UserRequest)
	Id: 14700 (0x396c)state: Wait (Reason: UserRequest)
	Id: 5396 (0x1514)state: Wait (Reason: EventPairLow)
	Id: 12604 (0x313c)state: Wait (Reason: EventPairLow)
	Id: 15012 (0x3aa4)state: Wait (Reason: EventPairLow)
	Id: 10924 (0x2aac)state: Wait (Reason: UserRequest)
	Id: 8136 (0x1fc8)state: Wait (Reason: UserRequest)
	Id: 12700 (0x319c)state: Wait (Reason: UserRequest)
	Id: 11244 (0x2bec)state: Wait (Reason: EventPairLow)
	Id: 15260 (0x3b9c)state: Wait (Reason: ExecutionDelay)
	Id: 2212 (0x08a4)state: Wait (Reason: UserRequest)
	Id: 3268 (0x0cc4)state: Wait (Reason: UserRequest)
	Id: 13656 (0x3558)state: Wait (Reason: ExecutionDelay)
	Id: 13864 (0x3628)state: Wait (Reason: UserRequest)
	Id: 13552 (0x34f0)state: Wait (Reason: UserRequest)
	Id: 4776 (0x12a8)state: Wait (Reason: UserRequest)
	Id: 14984 (0x3a88)state: Wait (Reason: ExecutionDelay)
	Id: 9196 (0x23ec)state: Wait (Reason: UserRequest)
	Id: 14896 (0x3a30)state: Wait (Reason: UserRequest)
	Id: 4080 (0x0ff0)state: Wait (Reason: UserRequest)
	Id: 10716 (0x29dc)state: Wait (Reason: UserRequest)
	Id: 2624 (0x0a40)state: Wait (Reason: UserRequest)
	Id: 8000 (0x1f40)state: Wait (Reason: UserRequest)
	Id: 15104 (0x3b00)state: Wait (Reason: UserRequest)
	Id: 15340 (0x3bec)state: Wait (Reason: EventPairLow)
	Id: 15400 (0x3c28)state: Wait (Reason: UserRequest)
	Id: 15404 (0x3c2c)state: Wait (Reason: UserRequest)
	Id: 15408 (0x3c30)state: Wait (Reason: UserRequest)
	Id: 15412 (0x3c34)state: Wait (Reason: UserRequest)
	Id: 15416 (0x3c38)state: Wait (Reason: UserRequest)
	Id: 15420 (0x3c3c)state: Wait (Reason: UserRequest)
	Id: 15424 (0x3c40)state: Wait (Reason: UserRequest)
	Id: 15428 (0x3c44)state: Wait (Reason: UserRequest)
	Id: 15432 (0x3c48)state: Wait (Reason: UserRequest)
	Id: 15444 (0x3c54)state: Wait (Reason: ExecutionDelay)
	Id: 15448 (0x3c58)state: Wait (Reason: UserRequest)
	Id: 15452 (0x3c5c)state: Wait (Reason: UserRequest)
	Id: 15456 (0x3c60)state: Wait (Reason: UserRequest)
	Id: 15460 (0x3c64)state: Wait (Reason: UserRequest)
	Id: 15464 (0x3c68)state: Wait (Reason: UserRequest)
	Id: 15468 (0x3c6c)state: Wait (Reason: UserRequest)
	Id: 15476 (0x3c74)state: Wait (Reason: UserRequest)
	Id: 15480 (0x3c78)state: Wait (Reason: UserRequest)
	Id: 15484 (0x3c7c)state: Wait (Reason: UserRequest)
	Id: 15488 (0x3c80)state: Wait (Reason: UserRequest)
	Id: 15492 (0x3c84)state: Wait (Reason: UserRequest)
	Id: 15508 (0x3c94)state: Wait (Reason: UserRequest)
	Id: 15512 (0x3c98)state: Wait (Reason: UserRequest)
	Id: 15612 (0x3cfc)state: Wait (Reason: EventPairLow)
	Id: 15616 (0x3d00)state: Wait (Reason: UserRequest)
	Id: 15668 (0x3d34)state: Wait (Reason: UserRequest)
	Id: 15692 (0x3d4c)state: Wait (Reason: UserRequest)
	Id: 15808 (0x3dc0)state: Wait (Reason: UserRequest)
	Id: 15812 (0x3dc4)state: Wait (Reason: UserRequest)
	Id: 8408 (0x20d8) (CURRENT)
		Start address: 0x0000000000000000
		State: Running
		Priority: 15
		Priority level: TimeCritical
		Start time: 19.08.2018 07:22:50
		Total processor time: 00:00:33.2343750
		User processor time: 00:00:33.2343750

	Id: 14404 (0x3844)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:22:50
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 13160 (0x3368)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:22:50
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 8332 (0x208c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:22:50
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 2836 (0x0b14)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:22:50
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 8420 (0x20e4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:22:50
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15316 (0x3bd4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:22:50
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 2092 (0x082c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: ExecutionDelay)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 1720 (0x06b8)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:02.2343750
		User processor time: 00:00:02.2343750

	Id: 3056 (0x0bf0)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 12896 (0x3260)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00.3593750
		User processor time: 00:00:00.3593750

	Id: 7496 (0x1d48)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: ExecutionDelay)
		Priority: 15
		Priority level: TimeCritical
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15236 (0x3b84)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 13832 (0x3608)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 6292 (0x1894)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15040 (0x3ac0)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 12644 (0x3164)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 7308 (0x1c8c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00.3750000
		User processor time: 00:00:00.3750000

	Id: 14676 (0x3954)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:02.7500000
		User processor time: 00:00:02.7500000

	Id: 13008 (0x32d0)
		Start address: 0x00007ffabb111410
		State: Running
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:01.2031250
		User processor time: 00:00:01.2031250

	Id: 11520 (0x2d00)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 8600 (0x2198)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 7104 (0x1bc0)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 2740 (0x0ab4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 5704 (0x1648)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00.3593750
		User processor time: 00:00:00.3593750

	Id: 10996 (0x2af4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00.6250000
		User processor time: 00:00:00.6250000

	Id: 1696 (0x06a0)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00.5156250
		User processor time: 00:00:00.5156250

	Id: 10568 (0x2948)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 19.08.2018 07:23:15
		Total processor time: 00:00:00.4843750
		User processor time: 00:00:00.4843750

	Id: 8052 (0x1f74)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:16
		Total processor time: 00:00:00.0312500
		User processor time: 00:00:00.0312500

	Id: 10136 (0x2798)
		Start address: 0x00007ffabb111410
		State: Running
		Priority: 11
		Priority level: Normal
		Start time: 19.08.2018 07:23:16
		Total processor time: 00:00:01.5937500
		User processor time: 00:00:01.5937500

	Id: 11108 (0x2b64)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00.0937500
		User processor time: 00:00:00.0937500

	Id: 3960 (0x0f78)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 14732 (0x398c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 13
		Priority level: Highest
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 4616 (0x1208)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: ExecutionDelay)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 14592 (0x3900)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 14
		Priority level: Highest
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 11304 (0x2c28)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 3548 (0x0ddc)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 13484 (0x34ac)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 11124 (0x2b74)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 14488 (0x3898)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 22
		Priority level: 14
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00.1406250
		User processor time: 00:00:00.1406250

	Id: 4588 (0x11ec)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: ExecutionDelay)
		Priority: 15
		Priority level: TimeCritical
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:01.9687500
		User processor time: 00:00:01.9687500

	Id: 8024 (0x1f58)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 14844 (0x39fc)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 5160 (0x1428)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:17
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 8404 (0x20d4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:18
		Total processor time: 00:00:00.0312500
		User processor time: 00:00:00.0312500

	Id: 11796 (0x2e14)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:18
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 3808 (0x0ee0)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:18
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 11492 (0x2ce4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 19.08.2018 07:23:18
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 4752 (0x1290)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 19.08.2018 07:23:18
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 6216 (0x1848)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 19.08.2018 07:23:18
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 12976 (0x32b0)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 5
		Priority level: Idle
		Start time: 19.08.2018 07:23:18
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 13624 (0x3538)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:18
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 14700 (0x396c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:19
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 5396 (0x1514)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 11
		Priority level: Normal
		Start time: 19.08.2018 07:23:19
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 12604 (0x313c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 10
		Priority level: Normal
		Start time: 19.08.2018 07:23:19
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15012 (0x3aa4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 10
		Priority level: Normal
		Start time: 19.08.2018 07:23:19
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 10924 (0x2aac)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:20
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 8136 (0x1fc8)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:20
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 12700 (0x319c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:20
		Total processor time: 00:00:00.0781250
		User processor time: 00:00:00.0781250

	Id: 11244 (0x2bec)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:20
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15260 (0x3b9c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: ExecutionDelay)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:20
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 2212 (0x08a4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:20
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 3268 (0x0cc4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:20
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 13656 (0x3558)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: ExecutionDelay)
		Priority: 7
		Priority level: BelowNormal
		Start time: 19.08.2018 07:23:20
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 13864 (0x3628)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:21
		Total processor time: 00:00:00.3750000
		User processor time: 00:00:00.3750000

	Id: 13552 (0x34f0)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:21
		Total processor time: 00:00:00.1562500
		User processor time: 00:00:00.1562500

	Id: 4776 (0x12a8)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:21
		Total processor time: 00:00:00.3593750
		User processor time: 00:00:00.3593750

	Id: 14984 (0x3a88)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: ExecutionDelay)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:21
		Total processor time: 00:00:00.0468750
		User processor time: 00:00:00.0468750

	Id: 9196 (0x23ec)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:22
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 14896 (0x3a30)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 19.08.2018 07:23:22
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 4080 (0x0ff0)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 19.08.2018 07:23:22
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 10716 (0x29dc)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 19.08.2018 07:23:22
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 2624 (0x0a40)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 22
		Priority level: 14
		Start time: 19.08.2018 07:23:22
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 8000 (0x1f40)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 15
		Priority level: TimeCritical
		Start time: 19.08.2018 07:23:22
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 15104 (0x3b00)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:22
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15340 (0x3bec)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:22
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15400 (0x3c28)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:23
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15404 (0x3c2c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:23
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15408 (0x3c30)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:23
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15412 (0x3c34)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:23
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15416 (0x3c38)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 7
		Priority level: BelowNormal
		Start time: 19.08.2018 07:23:23
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15420 (0x3c3c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:23
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15424 (0x3c40)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:23
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15428 (0x3c44)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:23
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15432 (0x3c48)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:23
		Total processor time: 00:00:00.0312500
		User processor time: 00:00:00.0312500

	Id: 15444 (0x3c54)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: ExecutionDelay)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

	Id: 15448 (0x3c58)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15452 (0x3c5c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15456 (0x3c60)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 9
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15460 (0x3c64)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15464 (0x3c68)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15468 (0x3c6c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 6
		Priority level: Lowest
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15476 (0x3c74)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15480 (0x3c78)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15484 (0x3c7c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15488 (0x3c80)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15492 (0x3c84)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 10
		Priority level: Highest
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15508 (0x3c94)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15512 (0x3c98)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:24
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15612 (0x3cfc)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: EventPairLow)
		Priority: 13
		Priority level: AboveNormal
		Start time: 19.08.2018 07:23:34
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15616 (0x3d00)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:34
		Total processor time: 00:00:00.2812500
		User processor time: 00:00:00.2812500

	Id: 15668 (0x3d34)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 8
		Priority level: Normal
		Start time: 19.08.2018 07:23:44
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15692 (0x3d4c)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:48
		Total processor time: 00:00:00
		User processor time: 00:00:00

	Id: 15808 (0x3dc0)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 12
		Priority level: Normal
		Start time: 19.08.2018 07:23:51
		Total processor time: 00:00:00.0781250
		User processor time: 00:00:00.0781250

	Id: 15812 (0x3dc4)
		Start address: 0x00007ffabb111410
		State: Wait (Reason: UserRequest)
		Priority: 11
		Priority level: Normal
		Start time: 19.08.2018 07:23:51
		Total processor time: 00:00:00.0156250
		User processor time: 00:00:00.0156250

Modules:
	Name: GTA5.exe; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe (Grand Theft Auto V v1.0.1493.0, by Rockstar Games)
	Name: ntdll.dll; path: C:\WINDOWS\SYSTEM32\ntdll.dll (Betriebssystem Microsoft® Windows® v10.0.17134.228, by Microsoft Corporation)
	Name: KERNEL32.DLL; path: C:\WINDOWS\System32\KERNEL32.DLL (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: KERNELBASE.dll; path: C:\WINDOWS\System32\KERNELBASE.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: apphelp.dll; path: C:\WINDOWS\SYSTEM32\apphelp.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: AcGenral.DLL; path: C:\WINDOWS\SYSTEM32\AcGenral.DLL (Microsoft® Windows® Operating System v10.0.17134.165, by Microsoft Corporation)
	Name: msvcrt.dll; path: C:\WINDOWS\System32\msvcrt.dll (Microsoft® Windows® Operating System v7.0.17134.1, by Microsoft Corporation)
	Name: sechost.dll; path: C:\WINDOWS\System32\sechost.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: RPCRT4.dll; path: C:\WINDOWS\System32\RPCRT4.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: SHLWAPI.dll; path: C:\WINDOWS\System32\SHLWAPI.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: combase.dll; path: C:\WINDOWS\System32\combase.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: ucrtbase.dll; path: C:\WINDOWS\System32\ucrtbase.dll (Microsoft® Windows® Operating System v10.0.17134.191, by Microsoft Corporation)
	Name: bcryptPrimitives.dll; path: C:\WINDOWS\System32\bcryptPrimitives.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: GDI32.dll; path: C:\WINDOWS\System32\GDI32.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: gdi32full.dll; path: C:\WINDOWS\System32\gdi32full.dll (Microsoft® Windows® Operating System v10.0.17134.112, by Microsoft Corporation)
	Name: msvcp_win.dll; path: C:\WINDOWS\System32\msvcp_win.dll (Microsoft® Windows® Operating System v10.0.17134.137, by Microsoft Corporation)
	Name: USER32.dll; path: C:\WINDOWS\System32\USER32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: win32u.dll; path: C:\WINDOWS\System32\win32u.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: ole32.dll; path: C:\WINDOWS\System32\ole32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: SHELL32.dll; path: C:\WINDOWS\System32\SHELL32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: cfgmgr32.dll; path: C:\WINDOWS\System32\cfgmgr32.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: shcore.dll; path: C:\WINDOWS\System32\shcore.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: windows.storage.dll; path: C:\WINDOWS\System32\windows.storage.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: advapi32.dll; path: C:\WINDOWS\System32\advapi32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: kernel.appcore.dll; path: C:\WINDOWS\System32\kernel.appcore.dll (Microsoft® Windows® Operating System v10.0.17134.112, by Microsoft Corporation)
	Name: profapi.dll; path: C:\WINDOWS\System32\profapi.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: powrprof.dll; path: C:\WINDOWS\System32\powrprof.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: FLTLIB.DLL; path: C:\WINDOWS\System32\FLTLIB.DLL (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: SspiCli.dll; path: C:\WINDOWS\SYSTEM32\SspiCli.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: USERENV.dll; path: C:\WINDOWS\SYSTEM32\USERENV.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: MPR.dll; path: C:\WINDOWS\SYSTEM32\MPR.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: IMM32.DLL; path: C:\WINDOWS\System32\IMM32.DLL (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: WS2_32.dll; path: C:\WINDOWS\System32\WS2_32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: PSAPI.DLL; path: C:\WINDOWS\System32\PSAPI.DLL (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: CRYPT32.dll; path: C:\WINDOWS\System32\CRYPT32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: MSASN1.dll; path: C:\WINDOWS\System32\MSASN1.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: WINTRUST.dll; path: C:\WINDOWS\System32\WINTRUST.dll (Microsoft® Windows® Operating System v10.0.17134.81, by Microsoft Corporation)
	Name: VERSION.dll; path: C:\WINDOWS\SYSTEM32\VERSION.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: OLEAUT32.dll; path: C:\WINDOWS\System32\OLEAUT32.dll (Microsoft® Windows® Operating System v10.0.17134.48, by Microsoft Corporation)
	Name: GFSDK_ShadowLib.win64.dll; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\GFSDK_ShadowLib.win64.dll ( v, by )
	Name: DSOUND.dll; path: C:\WINDOWS\SYSTEM32\DSOUND.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: bink2w64.dll; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\bink2w64.dll (Bink and Smacker v1.994a, by RAD Game Tools, Inc.)
	Name: MF.dll; path: C:\WINDOWS\SYSTEM32\MF.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: MFPlat.DLL; path: C:\WINDOWS\SYSTEM32\MFPlat.DLL (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: msdmo.dll; path: C:\WINDOWS\SYSTEM32\msdmo.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: MFReadWrite.dll; path: C:\WINDOWS\SYSTEM32\MFReadWrite.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: PROPSYS.dll; path: C:\WINDOWS\SYSTEM32\PROPSYS.dll (Windows® Search v7.0.17134.165, by Microsoft Corporation)
	Name: WTSAPI32.dll; path: C:\WINDOWS\SYSTEM32\WTSAPI32.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: d3d9.dll; path: C:\WINDOWS\SYSTEM32\d3d9.dll (Microsoft® Windows® Operating System v10.0.17134.81, by Microsoft Corporation)
	Name: D3DCOMPILER_43.dll; path: C:\WINDOWS\SYSTEM32\D3DCOMPILER_43.dll (Microsoft® DirectX for Windows® v9.29.952.3111, by Microsoft Corporation)
	Name: GFSDK_TXAA_AlphaResolve.win64.dll; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\GFSDK_TXAA_AlphaResolve.win64.dll ( v, by )
	Name: DINPUT8.dll; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\DINPUT8.dll (GTA V Asi loader v1.0.0.1, by Alexander Blade)
	Name: XINPUT1_3.dll; path: C:\WINDOWS\SYSTEM32\XINPUT1_3.dll (Microsoft® DirectX for Windows® v9.18.944.0000, by Microsoft Corporation)
	Name: SETUPAPI.dll; path: C:\WINDOWS\System32\SETUPAPI.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: IPHLPAPI.DLL; path: C:\WINDOWS\SYSTEM32\IPHLPAPI.DLL (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: WINMM.dll; path: C:\WINDOWS\SYSTEM32\WINMM.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: d3dx9_43.dll; path: C:\WINDOWS\SYSTEM32\d3dx9_43.dll (Microsoft® DirectX for Windows® v9.29.952.3111, by Microsoft Corporation)
	Name: dwmapi.dll; path: C:\WINDOWS\SYSTEM32\dwmapi.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: OPENGL32.dll; path: C:\WINDOWS\SYSTEM32\OPENGL32.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: GLU32.dll; path: C:\WINDOWS\SYSTEM32\GLU32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: MFCORE.DLL; path: C:\WINDOWS\SYSTEM32\MFCORE.DLL (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: ksuser.dll; path: C:\WINDOWS\SYSTEM32\ksuser.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: bcrypt.dll; path: C:\WINDOWS\SYSTEM32\bcrypt.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: CRYPTBASE.DLL; path: C:\WINDOWS\SYSTEM32\CRYPTBASE.DLL (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: winmmbase.dll; path: C:\WINDOWS\SYSTEM32\winmmbase.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: RTWorkQ.DLL; path: C:\WINDOWS\SYSTEM32\RTWorkQ.DLL (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: dinput8.dll; path: C:\WINDOWS\system32\dinput8.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: inputhost.dll; path: C:\WINDOWS\SYSTEM32\inputhost.dll ( v, by )
	Name: wintypes.dll; path: C:\WINDOWS\SYSTEM32\wintypes.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: CoreMessaging.dll; path: C:\WINDOWS\SYSTEM32\CoreMessaging.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: CoreUIComponents.dll; path: C:\WINDOWS\SYSTEM32\CoreUIComponents.dll (Microsoft® Windows® Operating System v10.0.17134.112, by Microsoft Corporation)
	Name: ntmarta.dll; path: C:\WINDOWS\SYSTEM32\ntmarta.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: AddonSpawner.asi; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\AddonSpawner.asi ( v, by )
	Name: ScriptHookV.dll; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\ScriptHookV.dll (ScriptHookV v1.0.1493.0, by Alexander Blade)
	Name: d3dx11_43.dll; path: C:\WINDOWS\SYSTEM32\d3dx11_43.dll (Microsoft® DirectX for Windows® v9.29.952.3111, by Microsoft Corporation)
	Name: AdvancedHookV.asi; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\AdvancedHookV.asi ( v, by )
	Name: MSVCP140.dll; path: C:\WINDOWS\SYSTEM32\MSVCP140.dll (Microsoft® Visual Studio® 2017 v14.13.26020.0, by Microsoft Corporation)
	Name: VCRUNTIME140.dll; path: C:\WINDOWS\SYSTEM32\VCRUNTIME140.dll (Microsoft® Visual Studio® 2017 v14.13.26020.0, by Microsoft Corporation)
	Name: LUA.asi; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\LUA.asi (Lua Plugin by Headscript v1.0.0.1, by Headscript)
	Name: MSVCR120.dll; path: C:\WINDOWS\SYSTEM32\MSVCR120.dll (Microsoft® Visual Studio® 2013 v12.00.21005.1, by Microsoft Corporation)
	Name: MSVCP120.dll; path: C:\WINDOWS\SYSTEM32\MSVCP120.dll (Microsoft® Visual Studio® 2013 v12.00.21005.1, by Microsoft Corporation)
	Name: openCameraV.asi; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\openCameraV.asi (openCamera for GTAV v1.0.0.1, by OpenIV Dev. Team)
	Name: OpenIV.asi; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\OpenIV.asi (OpenIV v2.0.0.0, by OpenIV Team)
	Name: ScriptHookVDotNet.asi; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\ScriptHookVDotNet.asi ( v, by )
	Name: mscoree.dll; path: C:\WINDOWS\SYSTEM32\mscoree.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: mscoreei.dll; path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll (Microsoft® .NET Framework v4.7.3056.0, by Microsoft Corporation)
	Name: TrainerV.asi; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\TrainerV.asi ( v, by )
	Name: LogitechLed.dll; path: C:\Program Files\Logitech Gaming Software\SDK\LED\x64\LogitechLed.dll (Logitech Gaming Framework v8.96.88, by Logitech Inc.)
	Name: imagehlp.dll; path: C:\WINDOWS\System32\imagehlp.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: CRYPTSP.dll; path: C:\WINDOWS\SYSTEM32\CRYPTSP.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: rsaenh.dll; path: C:\WINDOWS\system32\rsaenh.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: nvspcap64.dll; path: C:\WINDOWS\system32\nvspcap64.dll (NVIDIA GeForce Experience v3.13.1.30, by NVIDIA Corporation)
	Name: D3D11.DLL; path: C:\WINDOWS\SYSTEM32\D3D11.DLL (Microsoft® Windows® Operating System v10.0.17134.112, by Microsoft Corporation)
	Name: dxgi.dll; path: C:\WINDOWS\SYSTEM32\dxgi.dll (Microsoft® Windows® Operating System v10.0.17134.112, by Microsoft Corporation)
	Name: nvapi64.dll; path: C:\WINDOWS\system32\nvapi64.dll (NVIDIA Windows drivers v23.21.13.8813, by NVIDIA Corporation)
	Name: D3D10_1.DLL; path: C:\WINDOWS\SYSTEM32\D3D10_1.DLL (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: d3d10_1core.dll; path: C:\WINDOWS\SYSTEM32\d3d10_1core.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: uxtheme.dll; path: C:\WINDOWS\system32\uxtheme.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: MSCTF.dll; path: C:\WINDOWS\System32\MSCTF.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: TextInputFramework.dll; path: C:\WINDOWS\System32\TextInputFramework.dll (Microsoft® Windows® Operating System v10.0.17134.191, by Microsoft Corporation)
	Name: WINSTA.dll; path: C:\WINDOWS\SYSTEM32\WINSTA.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: nvldumdx.dll; path: C:\WINDOWS\System32\DriverStore\FileRepository\nv_ref_pubwu.inf_amd64_2e7fa54192fe16d0\nvldumdx.dll (NVIDIA driver loader v23.21.13.8813, by NVIDIA Corporation)
	Name: nvwgf2umx.dll; path: C:\WINDOWS\System32\DriverStore\FileRepository\nv_ref_pubwu.inf_amd64_2e7fa54192fe16d0\nvwgf2umx.dll (NVIDIA D3D10 drivers v23.21.13.8813, by NVIDIA Corporation)
	Name: dcomp.dll; path: C:\WINDOWS\SYSTEM32\dcomp.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: socialclub_tmp.dll; path: C:\Users\eroge\AppData\Local\Temp\1eeyd2gw4vnycncn\socialclub_tmp.dll (RAGE Plugin Hook v0.63.1224.15140, by MulleDK19 / LMS)
	Name: XINPUT9_1_0.dll; path: C:\WINDOWS\SYSTEM32\XINPUT9_1_0.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: FW1FontWrapper.dll; path: C:\Program Files\Rockstar Games\Grand Theft Auto V\FW1FontWrapper.dll ( v, by )
	Name: dbghelp.dll; path: C:\WINDOWS\SYSTEM32\dbghelp.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: dbgcore.DLL; path: C:\WINDOWS\SYSTEM32\dbgcore.DLL (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: clr.dll; path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clr.dll (Microsoft® .NET Framework v4.7.3132.0, by Microsoft Corporation)
	Name: MSVCR120_CLR0400.dll; path: C:\WINDOWS\SYSTEM32\MSVCR120_CLR0400.dll (Microsoft® Visual Studio® 2013 v12.00.52519.0, by Microsoft Corporation)
	Name: DiscordHook64.dll; path: C:\Users\eroge\AppData\Roaming\discord\0.0.301\modules\discord_hook\13\DiscordHook64.dll ( v, by )
	Name: mswsock.dll; path: C:\WINDOWS\system32\mswsock.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: mscorlib.ni.dll; path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\mscorlib\649c6a53d1a3a182e6eac793694a733f\mscorlib.ni.dll (Microsoft® .NET Framework v4.7.3132.0, by Microsoft Corporation)
	Name: clrjit.dll; path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clrjit.dll (Microsoft® .NET Framework v4.7.3132.0, by Microsoft Corporation)
	Name: diasymreader.dll; path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\diasymreader.dll (Microsoft® Visual Studio® 12 CTP v14.7.3056.0, by Microsoft Corporation)
	Name: System.ni.dll; path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System\7e7ba461137d6faf674666f208bb34c2\System.ni.dll (Microsoft® .NET Framework v4.7.3151.0, by Microsoft Corporation)
	Name: System.Drawing.ni.dll; path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Drawing\cf9625cf0f5fdb35d7171e09723e3fbb\System.Drawing.ni.dll (Microsoft® .NET Framework v4.7.3056.0, by Microsoft Corporation)
	Name: System.Windows.Forms.ni.dll; path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Windows.Forms\69ff356ffaef4c4c137570836532ba4d\System.Windows.Forms.ni.dll (Microsoft® .NET Framework v4.7.3056.0, by Microsoft Corporation)
	Name: HID.DLL; path: C:\WINDOWS\SYSTEM32\HID.DLL (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: DEVOBJ.dll; path: C:\WINDOWS\SYSTEM32\DEVOBJ.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: D3DCompiler_47.dll; path: C:\WINDOWS\SYSTEM32\D3DCompiler_47.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: clbcatq.dll; path: C:\WINDOWS\System32\clbcatq.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: MMDevApi.dll; path: C:\WINDOWS\System32\MMDevApi.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: XAudio2_7.dll; path: C:\WINDOWS\system32\XAudio2_7.dll (Microsoft® DirectX for Windows® v9.29.1962.0, by Microsoft Corporation)
	Name: AUDIOSES.DLL; path: C:\WINDOWS\SYSTEM32\AUDIOSES.DLL (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: AVRT.dll; path: C:\WINDOWS\SYSTEM32\AVRT.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: Windows.UI.dll; path: C:\Windows\System32\Windows.UI.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: System.Core.ni.dll; path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Core\6a9fe8d059ff70adb50f5b340a4ad8ee\System.Core.ni.dll (Microsoft® .NET Framework v4.7.3160.0, by Microsoft Corporation)
	Name: System.Xml.ni.dll; path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Xml\08e8fa67f0a711551a8a00ad6c5880fc\System.Xml.ni.dll (Microsoft® .NET Framework v4.7.3056.0, by Microsoft Corporation)
	Name: System.Configuration.ni.dll; path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Configuration\19daa5f5a704db96e4a812fa16f847fc\System.Configuration.ni.dll (Microsoft® .NET Framework v4.7.3056.0, by Microsoft Corporation)
	Name: comctl32.dll; path: C:\WINDOWS\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17134.228_none_fb4599993062b194\comctl32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.228, by Microsoft Corporation)
	Name: gdiplus.dll; path: C:\WINDOWS\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.17134.228_none_2c308c7e8af52b62\gdiplus.dll (Microsoft® Windows® Operating System v10.0.17134.228, by Microsoft Corporation)
	Name: DWrite.dll; path: C:\WINDOWS\SYSTEM32\DWrite.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: WindowsCodecs.dll; path: C:\WINDOWS\SYSTEM32\WindowsCodecs.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: IconCodecService.dll; path: C:\WINDOWS\system32\IconCodecService.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: gpapi.dll; path: C:\WINDOWS\SYSTEM32\gpapi.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: cryptnet.dll; path: C:\Windows\System32\cryptnet.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: WINNSI.DLL; path: C:\WINDOWS\SYSTEM32\WINNSI.DLL (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: NSI.dll; path: C:\WINDOWS\System32\NSI.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: socialclub.dll; path: C:\Program Files\Rockstar Games\Social Club\socialclub.dll (Social Club v1.2.4.0, by Take-Two Interactive Software, Inc.)
	Name: WININET.dll; path: C:\WINDOWS\SYSTEM32\WININET.dll (Internet Explorer v11.00.17134.165, by Microsoft Corporation)
	Name: napinsp.dll; path: C:\WINDOWS\system32\napinsp.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: pnrpnsp.dll; path: C:\WINDOWS\system32\pnrpnsp.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: NLAapi.dll; path: C:\WINDOWS\system32\NLAapi.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: DNSAPI.dll; path: C:\WINDOWS\SYSTEM32\DNSAPI.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: winrnr.dll; path: C:\WINDOWS\System32\winrnr.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: fwpuclnt.dll; path: C:\WINDOWS\System32\fwpuclnt.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: rasadhlp.dll; path: C:\Windows\System32\rasadhlp.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: FirewallAPI.dll; path: C:\Windows\System32\FirewallAPI.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: fwbase.dll; path: C:\Windows\System32\fwbase.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: FWPolicyIOMgr.dll; path: C:\Windows\System32\FWPolicyIOMgr.dll (Microsoft® Windows® Operating System v10.0.17134.137, by Microsoft Corporation)
	Name: wdmaud.drv; path: C:\WINDOWS\SYSTEM32\wdmaud.drv (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: msacm32.drv; path: C:\WINDOWS\SYSTEM32\msacm32.drv (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: MSACM32.dll; path: C:\WINDOWS\SYSTEM32\MSACM32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: midimap.dll; path: C:\WINDOWS\SYSTEM32\midimap.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: iertutil.dll; path: C:\WINDOWS\SYSTEM32\iertutil.dll (Internet Explorer v11.00.17134.165, by Microsoft Corporation)
	Name: ondemandconnroutehelper.dll; path: C:\WINDOWS\SYSTEM32\ondemandconnroutehelper.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: winhttp.dll; path: C:\WINDOWS\SYSTEM32\winhttp.dll (Betriebssystem Microsoft® Windows® v10.0.17134.165, by Microsoft Corporation)
	Name: wbemprox.dll; path: C:\WINDOWS\system32\wbem\wbemprox.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: wbemcomn.dll; path: C:\WINDOWS\SYSTEM32\wbemcomn.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: wbemsvc.dll; path: C:\WINDOWS\system32\wbem\wbemsvc.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: fastprox.dll; path: C:\WINDOWS\system32\wbem\fastprox.dll (Microsoft® Windows® Operating System v10.0.17134.1, by Microsoft Corporation)
	Name: comctl32.dll; path: C:\WINDOWS\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_5.82.17134.228_none_f95000f73097dead\comctl32.dll (Betriebssystem Microsoft® Windows® v10.0.17134.228, by Microsoft Corporation)
	Name: GTA5.exe
		Base address: 0x00007ff62bda0000
		Memory size: 0x053a3a00
		Entry point address: 0x00007ff62d4faa10
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe
		Product name: Grand Theft Auto V
		Product version: 1.0.1493.0
		Company: Rockstar Games

	Name: ntdll.dll
		Base address: 0x00007ffabb0a0000
		Memory size: 0x001e1000
		Entry point address: 0x0000000000000000
		File path: C:\WINDOWS\SYSTEM32\ntdll.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.228
		Company: Microsoft Corporation

	Name: KERNEL32.DLL
		Base address: 0x00007ffaba730000
		Memory size: 0x000b2000
		Entry point address: 0x00007ffaba7430c0
		File path: C:\WINDOWS\System32\KERNEL32.DLL
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: KERNELBASE.dll
		Base address: 0x00007ffab7910000
		Memory size: 0x00273000
		Entry point address: 0x00007ffab7917fa0
		File path: C:\WINDOWS\System32\KERNELBASE.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: apphelp.dll
		Base address: 0x00007ffab5840000
		Memory size: 0x0008b000
		Entry point address: 0x00007ffab58547e0
		File path: C:\WINDOWS\SYSTEM32\apphelp.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: AcGenral.DLL
		Base address: 0x00007ffaa7880000
		Memory size: 0x00059000
		Entry point address: 0x00007ffaa78823d0
		File path: C:\WINDOWS\SYSTEM32\AcGenral.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: msvcrt.dll
		Base address: 0x00007ffabacc0000
		Memory size: 0x0009e000
		Entry point address: 0x00007ffabacc77e0
		File path: C:\WINDOWS\System32\msvcrt.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 7.0.17134.1
		Company: Microsoft Corporation

	Name: sechost.dll
		Base address: 0x00007ffabb010000
		Memory size: 0x0005b000
		Entry point address: 0x00007ffabb01eab0
		File path: C:\WINDOWS\System32\sechost.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: RPCRT4.dll
		Base address: 0x00007ffaba600000
		Memory size: 0x00124000
		Entry point address: 0x00007ffaba609f70
		File path: C:\WINDOWS\System32\RPCRT4.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: SHLWAPI.dll
		Base address: 0x00007ffab8530000
		Memory size: 0x00051000
		Entry point address: 0x00007ffab853a010
		File path: C:\WINDOWS\System32\SHLWAPI.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: combase.dll
		Base address: 0x00007ffaba910000
		Memory size: 0x00323000
		Entry point address: 0x00007ffaba9e23c0
		File path: C:\WINDOWS\System32\combase.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: ucrtbase.dll
		Base address: 0x00007ffab7b90000
		Memory size: 0x000fa000
		Entry point address: 0x00007ffab7b96f50
		File path: C:\WINDOWS\System32\ucrtbase.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.191
		Company: Microsoft Corporation

	Name: bcryptPrimitives.dll
		Base address: 0x00007ffab8400000
		Memory size: 0x0007a000
		Entry point address: 0x00007ffab84391d0
		File path: C:\WINDOWS\System32\bcryptPrimitives.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: GDI32.dll
		Base address: 0x00007ffab9db0000
		Memory size: 0x00028000
		Entry point address: 0x00007ffab9db4040
		File path: C:\WINDOWS\System32\GDI32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: gdi32full.dll
		Base address: 0x00007ffab76d0000
		Memory size: 0x00192000
		Entry point address: 0x00007ffab7703c90
		File path: C:\WINDOWS\System32\gdi32full.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.112
		Company: Microsoft Corporation

	Name: msvcp_win.dll
		Base address: 0x00007ffab7870000
		Memory size: 0x0009f000
		Entry point address: 0x00007ffab7880860
		File path: C:\WINDOWS\System32\msvcp_win.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.137
		Company: Microsoft Corporation

	Name: USER32.dll
		Base address: 0x00007ffabad70000
		Memory size: 0x00190000
		Entry point address: 0x00007ffabad8bb30
		File path: C:\WINDOWS\System32\USER32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: win32u.dll
		Base address: 0x00007ffab74c0000
		Memory size: 0x00020000
		Entry point address: 0x0000000000000000
		File path: C:\WINDOWS\System32\win32u.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: ole32.dll
		Base address: 0x00007ffab8590000
		Memory size: 0x00151000
		Entry point address: 0x00007ffab85b3ba0
		File path: C:\WINDOWS\System32\ole32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: SHELL32.dll
		Base address: 0x00007ffab88a0000
		Memory size: 0x01440000
		Entry point address: 0x00007ffab897f8d0
		File path: C:\WINDOWS\System32\SHELL32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: cfgmgr32.dll
		Base address: 0x00007ffab7470000
		Memory size: 0x00049000
		Entry point address: 0x00007ffab7481cd0
		File path: C:\WINDOWS\System32\cfgmgr32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: shcore.dll
		Base address: 0x00007ffabaf60000
		Memory size: 0x000a9000
		Entry point address: 0x00007ffabaf9d310
		File path: C:\WINDOWS\System32\shcore.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: windows.storage.dll
		Base address: 0x00007ffab7c90000
		Memory size: 0x0070d000
		Entry point address: 0x00007ffab7e0a430
		File path: C:\WINDOWS\System32\windows.storage.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: advapi32.dll
		Base address: 0x00007ffaba860000
		Memory size: 0x000a1000
		Entry point address: 0x00007ffaba871b60
		File path: C:\WINDOWS\System32\advapi32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: kernel.appcore.dll
		Base address: 0x00007ffab73b0000
		Memory size: 0x00011000
		Entry point address: 0x00007ffab73b3b00
		File path: C:\WINDOWS\System32\kernel.appcore.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.112
		Company: Microsoft Corporation

	Name: profapi.dll
		Base address: 0x00007ffab7450000
		Memory size: 0x0001f000
		Entry point address: 0x00007ffab7456560
		File path: C:\WINDOWS\System32\profapi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: powrprof.dll
		Base address: 0x00007ffab73f0000
		Memory size: 0x0004c000
		Entry point address: 0x00007ffab73f3630
		File path: C:\WINDOWS\System32\powrprof.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: FLTLIB.DLL
		Base address: 0x00007ffab7440000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffab7442e00
		File path: C:\WINDOWS\System32\FLTLIB.DLL
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: SspiCli.dll
		Base address: 0x00007ffab72b0000
		Memory size: 0x00030000
		Entry point address: 0x00007ffab72bf9a0
		File path: C:\WINDOWS\SYSTEM32\SspiCli.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: USERENV.dll
		Base address: 0x00007ffab72e0000
		Memory size: 0x00028000
		Entry point address: 0x00007ffab72e4ba0
		File path: C:\WINDOWS\SYSTEM32\USERENV.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: MPR.dll
		Base address: 0x00007ffaa0140000
		Memory size: 0x0001a000
		Entry point address: 0x00007ffaa0142380
		File path: C:\WINDOWS\SYSTEM32\MPR.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: IMM32.DLL
		Base address: 0x00007ffaba5d0000
		Memory size: 0x0002d000
		Entry point address: 0x00007ffaba5d1640
		File path: C:\WINDOWS\System32\IMM32.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: WS2_32.dll
		Base address: 0x00007ffaba7f0000
		Memory size: 0x0006c000
		Entry point address: 0x00007ffaba8072b0
		File path: C:\WINDOWS\System32\WS2_32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: PSAPI.DLL
		Base address: 0x00007ffab86f0000
		Memory size: 0x00008000
		Entry point address: 0x00007ffab86f1080
		File path: C:\WINDOWS\System32\PSAPI.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: CRYPT32.dll
		Base address: 0x00007ffab74e0000
		Memory size: 0x001e2000
		Entry point address: 0x00007ffab753ce80
		File path: C:\WINDOWS\System32\CRYPT32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: MSASN1.dll
		Base address: 0x00007ffab73d0000
		Memory size: 0x00012000
		Entry point address: 0x00007ffab73d58b0
		File path: C:\WINDOWS\System32\MSASN1.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: WINTRUST.dll
		Base address: 0x00007ffab83a0000
		Memory size: 0x00057000
		Entry point address: 0x00007ffab83b0eb0
		File path: C:\WINDOWS\System32\WINTRUST.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.81
		Company: Microsoft Corporation

	Name: VERSION.dll
		Base address: 0x00007ffab2520000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffab2521300
		File path: C:\WINDOWS\SYSTEM32\VERSION.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: OLEAUT32.dll
		Base address: 0x00007ffab9ce0000
		Memory size: 0x000c2000
		Entry point address: 0x00007ffab9cf88d0
		File path: C:\WINDOWS\System32\OLEAUT32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.48
		Company: Microsoft Corporation

	Name: GFSDK_ShadowLib.win64.dll
		Base address: 0x00007ffa53100000
		Memory size: 0x003cc000
		Entry point address: 0x00007ffa5310cf10
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\GFSDK_ShadowLib.win64.dll
		Product name: 
		Product version: 
		Company: 

	Name: DSOUND.dll
		Base address: 0x00007ffa81f40000
		Memory size: 0x0008f000
		Entry point address: 0x00007ffa81f47210
		File path: C:\WINDOWS\SYSTEM32\DSOUND.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: bink2w64.dll
		Base address: 0x00007ffa8a5c0000
		Memory size: 0x0008d000
		Entry point address: 0x00007ffa8a5c3a78
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\bink2w64.dll
		Product name: Bink and Smacker
		Product version: 1.994a
		Company: RAD Game Tools, Inc.

	Name: MF.dll
		Base address: 0x00007ffa9e0c0000
		Memory size: 0x0007b000
		Entry point address: 0x00007ffa9e0cb1c0
		File path: C:\WINDOWS\SYSTEM32\MF.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: MFPlat.DLL
		Base address: 0x00007ffa91eb0000
		Memory size: 0x001db000
		Entry point address: 0x00007ffa91ed9150
		File path: C:\WINDOWS\SYSTEM32\MFPlat.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: msdmo.dll
		Base address: 0x00007ffaa4270000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffaa4271460
		File path: C:\WINDOWS\SYSTEM32\msdmo.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: MFReadWrite.dll
		Base address: 0x00007ffa808e0000
		Memory size: 0x000f8000
		Entry point address: 0x00007ffa8090af60
		File path: C:\WINDOWS\SYSTEM32\MFReadWrite.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: PROPSYS.dll
		Base address: 0x00007ffab3b70000
		Memory size: 0x001b4000
		Entry point address: 0x00007ffab3bb80a0
		File path: C:\WINDOWS\SYSTEM32\PROPSYS.dll
		Product name: Windows® Search
		Product version: 7.0.17134.165
		Company: Microsoft Corporation

	Name: WTSAPI32.dll
		Base address: 0x00007ffab3fd0000
		Memory size: 0x00013000
		Entry point address: 0x00007ffab3fd2720
		File path: C:\WINDOWS\SYSTEM32\WTSAPI32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: d3d9.dll
		Base address: 0x00007ffa83150000
		Memory size: 0x00197000
		Entry point address: 0x00007ffa831950a0
		File path: C:\WINDOWS\SYSTEM32\d3d9.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.81
		Company: Microsoft Corporation

	Name: D3DCOMPILER_43.dll
		Base address: 0x00007ffa93d20000
		Memory size: 0x0026f000
		Entry point address: 0x00007ffa93f5be5c
		File path: C:\WINDOWS\SYSTEM32\D3DCOMPILER_43.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.29.952.3111
		Company: Microsoft Corporation

	Name: GFSDK_TXAA_AlphaResolve.win64.dll
		Base address: 0x00007ffaa1ce0000
		Memory size: 0x0001c000
		Entry point address: 0x00007ffaa1ce493c
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\GFSDK_TXAA_AlphaResolve.win64.dll
		Product name: 
		Product version: 
		Company: 

	Name: DINPUT8.dll
		Base address: 0x00007ffaa0b50000
		Memory size: 0x00025000
		Entry point address: 0x00007ffaa0b53804
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\DINPUT8.dll
		Product name: GTA V Asi loader
		Product version: 1.0.0.1
		Company: Alexander Blade

	Name: XINPUT1_3.dll
		Base address: 0x0000000000400000
		Memory size: 0x0001e000
		Entry point address: 0x00000000004098e0
		File path: C:\WINDOWS\SYSTEM32\XINPUT1_3.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.18.944.0000
		Company: Microsoft Corporation

	Name: SETUPAPI.dll
		Base address: 0x00007ffab9f00000
		Memory size: 0x0044b000
		Entry point address: 0x00007ffab9f28d30
		File path: C:\WINDOWS\System32\SETUPAPI.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: IPHLPAPI.DLL
		Base address: 0x00007ffab69b0000
		Memory size: 0x00038000
		Entry point address: 0x00007ffab69bbc80
		File path: C:\WINDOWS\SYSTEM32\IPHLPAPI.DLL
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: WINMM.dll
		Base address: 0x00007ffab5630000
		Memory size: 0x00023000
		Entry point address: 0x00007ffab56335a0
		File path: C:\WINDOWS\SYSTEM32\WINMM.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: d3dx9_43.dll
		Base address: 0x00007ffa6b6d0000
		Memory size: 0x00263000
		Entry point address: 0x00007ffa6b8e5d1c
		File path: C:\WINDOWS\SYSTEM32\d3dx9_43.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.29.952.3111
		Company: Microsoft Corporation

	Name: dwmapi.dll
		Base address: 0x00007ffab5d50000
		Memory size: 0x00029000
		Entry point address: 0x00007ffab5d525c0
		File path: C:\WINDOWS\SYSTEM32\dwmapi.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: OPENGL32.dll
		Base address: 0x00007ffa96bc0000
		Memory size: 0x00120000
		Entry point address: 0x00007ffa96c96bc0
		File path: C:\WINDOWS\SYSTEM32\OPENGL32.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: GLU32.dll
		Base address: 0x00007ffa96b50000
		Memory size: 0x0002c000
		Entry point address: 0x00007ffa96b6d3c0
		File path: C:\WINDOWS\SYSTEM32\GLU32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: MFCORE.DLL
		Base address: 0x00007ffa81260000
		Memory size: 0x0042e000
		Entry point address: 0x00007ffa812e2e70
		File path: C:\WINDOWS\SYSTEM32\MFCORE.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: ksuser.dll
		Base address: 0x00007ffaa1cd0000
		Memory size: 0x00009000
		Entry point address: 0x00007ffaa1cd1c60
		File path: C:\WINDOWS\SYSTEM32\ksuser.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: bcrypt.dll
		Base address: 0x00007ffab6f10000
		Memory size: 0x00025000
		Entry point address: 0x00007ffab6f188d0
		File path: C:\WINDOWS\SYSTEM32\bcrypt.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: CRYPTBASE.DLL
		Base address: 0x00007ffab6e00000
		Memory size: 0x0000b000
		Entry point address: 0x00007ffab6e01e60
		File path: C:\WINDOWS\SYSTEM32\CRYPTBASE.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: winmmbase.dll
		Base address: 0x00007ffab5600000
		Memory size: 0x0002a000
		Entry point address: 0x00007ffab5605010
		File path: C:\WINDOWS\SYSTEM32\winmmbase.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: RTWorkQ.DLL
		Base address: 0x00007ffa9f460000
		Memory size: 0x0002e000
		Entry point address: 0x00007ffa9f469bf0
		File path: C:\WINDOWS\SYSTEM32\RTWorkQ.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: dinput8.dll
		Base address: 0x00007ffaaaab0000
		Memory size: 0x00043000
		Entry point address: 0x00007ffaaaaba6d0
		File path: C:\WINDOWS\system32\dinput8.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: inputhost.dll
		Base address: 0x00007ffaaff10000
		Memory size: 0x00079000
		Entry point address: 0x00007ffaaff5c1e0
		File path: C:\WINDOWS\SYSTEM32\inputhost.dll
		Product name: 
		Product version: 
		Company: 

	Name: wintypes.dll
		Base address: 0x00007ffab2f50000
		Memory size: 0x0014d000
		Entry point address: 0x00007ffab2f7a6f0
		File path: C:\WINDOWS\SYSTEM32\wintypes.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: CoreMessaging.dll
		Base address: 0x00007ffab5000000
		Memory size: 0x000da000
		Entry point address: 0x00007ffab5045c30
		File path: C:\WINDOWS\SYSTEM32\CoreMessaging.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: CoreUIComponents.dll
		Base address: 0x00007ffab10a0000
		Memory size: 0x0031e000
		Entry point address: 0x00007ffab11086e0
		File path: C:\WINDOWS\SYSTEM32\CoreUIComponents.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.112
		Company: Microsoft Corporation

	Name: ntmarta.dll
		Base address: 0x00007ffab64a0000
		Memory size: 0x00031000
		Entry point address: 0x00007ffab64a71f0
		File path: C:\WINDOWS\SYSTEM32\ntmarta.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: AddonSpawner.asi
		Base address: 0x00007ffa7b840000
		Memory size: 0x000d8000
		Entry point address: 0x00007ffa7b89b0b4
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\AddonSpawner.asi
		Product name: 
		Product version: 
		Company: 

	Name: ScriptHookV.dll
		Base address: 0x00007ffa708a0000
		Memory size: 0x00120000
		Entry point address: 0x00007ffa708ae5e8
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\ScriptHookV.dll
		Product name: ScriptHookV
		Product version: 1.0.1493.0
		Company: Alexander Blade

	Name: d3dx11_43.dll
		Base address: 0x00007ffaa0a60000
		Memory size: 0x00046000
		Entry point address: 0x00007ffaa0a97a2c
		File path: C:\WINDOWS\SYSTEM32\d3dx11_43.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.29.952.3111
		Company: Microsoft Corporation

	Name: AdvancedHookV.asi
		Base address: 0x00007ffaaa970000
		Memory size: 0x0000c000
		Entry point address: 0x00007ffaaa973840
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\AdvancedHookV.asi
		Product name: 
		Product version: 
		Company: 

	Name: MSVCP140.dll
		Base address: 0x00007ffa86ec0000
		Memory size: 0x000a7000
		Entry point address: 0x00007ffa86f16130
		File path: C:\WINDOWS\SYSTEM32\MSVCP140.dll
		Product name: Microsoft® Visual Studio® 2017
		Product version: 14.13.26020.0
		Company: Microsoft Corporation

	Name: VCRUNTIME140.dll
		Base address: 0x00007ffa9ba60000
		Memory size: 0x00016000
		Entry point address: 0x00007ffa9ba6c550
		File path: C:\WINDOWS\SYSTEM32\VCRUNTIME140.dll
		Product name: Microsoft® Visual Studio® 2017
		Product version: 14.13.26020.0
		Company: Microsoft Corporation

	Name: LUA.asi
		Base address: 0x00007ffa52da0000
		Memory size: 0x00360000
		Entry point address: 0x00007ffa53049f10
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\LUA.asi
		Product name: Lua Plugin by Headscript
		Product version: 1.0.0.1
		Company: Headscript

	Name: MSVCR120.dll
		Base address: 0x00007ffaa9260000
		Memory size: 0x000ef000
		Entry point address: 0x00007ffaa92829cc
		File path: C:\WINDOWS\SYSTEM32\MSVCR120.dll
		Product name: Microsoft® Visual Studio® 2013
		Product version: 12.00.21005.1
		Company: Microsoft Corporation

	Name: MSVCP120.dll
		Base address: 0x00007ffaa91b0000
		Memory size: 0x000a6000
		Entry point address: 0x00007ffaa91fefec
		File path: C:\WINDOWS\SYSTEM32\MSVCP120.dll
		Product name: Microsoft® Visual Studio® 2013
		Product version: 12.00.21005.1
		Company: Microsoft Corporation

	Name: openCameraV.asi
		Base address: 0x00007ffa9fc90000
		Memory size: 0x00024000
		Entry point address: 0x00007ffa9fc92994
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\openCameraV.asi
		Product name: openCamera for GTAV
		Product version: 1.0.0.1
		Company: OpenIV Dev. Team

	Name: OpenIV.asi
		Base address: 0x00007ffa9fa00000
		Memory size: 0x00027000
		Entry point address: 0x00007ffa9fa02cdc
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\OpenIV.asi
		Product name: OpenIV
		Product version: 2.0.0.0
		Company: OpenIV Team

	Name: ScriptHookVDotNet.asi
		Base address: 0x00007ffaa7920000
		Memory size: 0x0000e000
		Entry point address: 0x00007ffaa7922d92
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\ScriptHookVDotNet.asi
		Product name: 
		Product version: 
		Company: 

	Name: mscoree.dll
		Base address: 0x00007ffa9f0e0000
		Memory size: 0x00064000
		Entry point address: 0x00007ffa9f109e20
		File path: C:\WINDOWS\SYSTEM32\mscoree.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: mscoreei.dll
		Base address: 0x00007ffa9f040000
		Memory size: 0x0009c000
		Entry point address: 0x00007ffa9f047a70
		File path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3056.0
		Company: Microsoft Corporation

	Name: TrainerV.asi
		Base address: 0x00007ffa51eb0000
		Memory size: 0x00eed000
		Entry point address: 0x00007ffa521d91a4
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\TrainerV.asi
		Product name: 
		Product version: 
		Company: 

	Name: LogitechLed.dll
		Base address: 0x00007ffa976a0000
		Memory size: 0x00028000
		Entry point address: 0x00007ffa976b4994
		File path: C:\Program Files\Logitech Gaming Software\SDK\LED\x64\LogitechLed.dll
		Product name: Logitech Gaming Framework
		Product version: 8.96.88
		Company: Logitech Inc.

	Name: imagehlp.dll
		Base address: 0x00007ffab9ed0000
		Memory size: 0x0001d000
		Entry point address: 0x00007ffab9ed2b60
		File path: C:\WINDOWS\System32\imagehlp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: CRYPTSP.dll
		Base address: 0x00007ffab6de0000
		Memory size: 0x00017000
		Entry point address: 0x00007ffab6de4c60
		File path: C:\WINDOWS\SYSTEM32\CRYPTSP.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: rsaenh.dll
		Base address: 0x00007ffab6810000
		Memory size: 0x00033000
		Entry point address: 0x00007ffab681b040
		File path: C:\WINDOWS\system32\rsaenh.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: nvspcap64.dll
		Base address: 0x00007ffaa5150000
		Memory size: 0x00266000
		Entry point address: 0x00007ffaa51581ca
		File path: C:\WINDOWS\system32\nvspcap64.dll
		Product name: NVIDIA GeForce Experience
		Product version: 3.13.1.30
		Company: NVIDIA Corporation

	Name: D3D11.DLL
		Base address: 0x00007ffab4820000
		Memory size: 0x0030b000
		Entry point address: 0x00007ffab48acef0
		File path: C:\WINDOWS\SYSTEM32\D3D11.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.112
		Company: Microsoft Corporation

	Name: dxgi.dll
		Base address: 0x00007ffab6240000
		Memory size: 0x000bb000
		Entry point address: 0x00007ffab62649c0
		File path: C:\WINDOWS\SYSTEM32\dxgi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.112
		Company: Microsoft Corporation

	Name: nvapi64.dll
		Base address: 0x00007ffaaed60000
		Memory size: 0x00480000
		Entry point address: 0x00007ffaaf0942e4
		File path: C:\WINDOWS\system32\nvapi64.dll
		Product name: NVIDIA Windows drivers
		Product version: 23.21.13.8813
		Company: NVIDIA Corporation

	Name: D3D10_1.DLL
		Base address: 0x00007ffa96b80000
		Memory size: 0x00031000
		Entry point address: 0x00007ffa96b9f720
		File path: C:\WINDOWS\SYSTEM32\D3D10_1.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: d3d10_1core.dll
		Base address: 0x00007ffa96af0000
		Memory size: 0x0005a000
		Entry point address: 0x00007ffa96af1ce0
		File path: C:\WINDOWS\SYSTEM32\d3d10_1core.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: uxtheme.dll
		Base address: 0x00007ffab5a70000
		Memory size: 0x00098000
		Entry point address: 0x00007ffab5a94800
		File path: C:\WINDOWS\system32\uxtheme.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: MSCTF.dll
		Base address: 0x00007ffaba3f0000
		Memory size: 0x00175000
		Entry point address: 0x00007ffaba436dc0
		File path: C:\WINDOWS\System32\MSCTF.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: TextInputFramework.dll
		Base address: 0x00007ffaaf650000
		Memory size: 0x00097000
		Entry point address: 0x00007ffaaf679980
		File path: C:\WINDOWS\System32\TextInputFramework.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.191
		Company: Microsoft Corporation

	Name: WINSTA.dll
		Base address: 0x00007ffab67b0000
		Memory size: 0x00056000
		Entry point address: 0x00007ffab67bbd00
		File path: C:\WINDOWS\SYSTEM32\WINSTA.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: nvldumdx.dll
		Base address: 0x00007ffab0340000
		Memory size: 0x000ea000
		Entry point address: 0x00007ffab034c8a0
		File path: C:\WINDOWS\System32\DriverStore\FileRepository\nv_ref_pubwu.inf_amd64_2e7fa54192fe16d0\nvldumdx.dll
		Product name: NVIDIA driver loader
		Product version: 23.21.13.8813
		Company: NVIDIA Corporation

	Name: nvwgf2umx.dll
		Base address: 0x00007ffa95000000
		Memory size: 0x01aec000
		Entry point address: 0x00007ffa95065370
		File path: C:\WINDOWS\System32\DriverStore\FileRepository\nv_ref_pubwu.inf_amd64_2e7fa54192fe16d0\nvwgf2umx.dll
		Product name: NVIDIA D3D10 drivers
		Product version: 23.21.13.8813
		Company: NVIDIA Corporation

	Name: dcomp.dll
		Base address: 0x00007ffab50e0000
		Memory size: 0x0019c000
		Entry point address: 0x00007ffab5147de0
		File path: C:\WINDOWS\SYSTEM32\dcomp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: socialclub_tmp.dll
		Base address: 0x0000000c00000000
		Memory size: 0x00f1a000
		Entry point address: 0x0000000c00f15000
		File path: C:\Users\eroge\AppData\Local\Temp\1eeyd2gw4vnycncn\socialclub_tmp.dll
		Product name: RAGE Plugin Hook
		Product version: 0.63.1224.15140
		Company: MulleDK19 / LMS

	Name: XINPUT9_1_0.dll
		Base address: 0x00007ffaa15c0000
		Memory size: 0x00007000
		Entry point address: 0x00007ffaa15c1500
		File path: C:\WINDOWS\SYSTEM32\XINPUT9_1_0.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: FW1FontWrapper.dll
		Base address: 0x00007ffa8f050000
		Memory size: 0x0002a000
		Entry point address: 0x00007ffa8f05e94c
		File path: C:\Program Files\Rockstar Games\Grand Theft Auto V\FW1FontWrapper.dll
		Product name: 
		Product version: 
		Company: 

	Name: dbghelp.dll
		Base address: 0x00007ffaa6470000
		Memory size: 0x001c9000
		Entry point address: 0x00007ffaa6478c10
		File path: C:\WINDOWS\SYSTEM32\dbghelp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: dbgcore.DLL
		Base address: 0x00007ffaa6440000
		Memory size: 0x00029000
		Entry point address: 0x00007ffaa6458c50
		File path: C:\WINDOWS\SYSTEM32\dbgcore.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: clr.dll
		Base address: 0x00007ffa75190000
		Memory size: 0x009ec000
		Entry point address: 0x00007ffa751963f0
		File path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clr.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3132.0
		Company: Microsoft Corporation

	Name: MSVCR120_CLR0400.dll
		Base address: 0x00007ffaa0b80000
		Memory size: 0x000f7000
		Entry point address: 0x00007ffaa0ba4db0
		File path: C:\WINDOWS\SYSTEM32\MSVCR120_CLR0400.dll
		Product name: Microsoft® Visual Studio® 2013
		Product version: 12.00.52519.0
		Company: Microsoft Corporation

	Name: DiscordHook64.dll
		Base address: 0x00007ffa51be0000
		Memory size: 0x002d0000
		Entry point address: 0x00007ffa51bed436
		File path: C:\Users\eroge\AppData\Roaming\discord\0.0.301\modules\discord_hook\13\DiscordHook64.dll
		Product name: 
		Product version: 
		Company: 

	Name: mswsock.dll
		Base address: 0x00007ffab6c30000
		Memory size: 0x00066000
		Entry point address: 0x00007ffab6c412c0
		File path: C:\WINDOWS\system32\mswsock.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: mscorlib.ni.dll
		Base address: 0x00007ffa6d3e0000
		Memory size: 0x01588000
		Entry point address: 0x0000000000000000
		File path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\mscorlib\649c6a53d1a3a182e6eac793694a733f\mscorlib.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3132.0
		Company: Microsoft Corporation

	Name: clrjit.dll
		Base address: 0x00007ffa884c0000
		Memory size: 0x0012c000
		Entry point address: 0x00007ffa884c1080
		File path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\clrjit.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3132.0
		Company: Microsoft Corporation

	Name: diasymreader.dll
		Base address: 0x00007ffa51aa0000
		Memory size: 0x00138000
		Entry point address: 0x00007ffa51ac7fb0
		File path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\diasymreader.dll
		Product name: Microsoft® Visual Studio® 12 CTP
		Product version: 14.7.3056.0
		Company: Microsoft Corporation

	Name: System.ni.dll
		Base address: 0x00007ffa732f0000
		Memory size: 0x00c3f000
		Entry point address: 0x0000000000000000
		File path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System\7e7ba461137d6faf674666f208bb34c2\System.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3151.0
		Company: Microsoft Corporation

	Name: System.Drawing.ni.dll
		Base address: 0x00007ffa747d0000
		Memory size: 0x001e8000
		Entry point address: 0x0000000000000000
		File path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Drawing\cf9625cf0f5fdb35d7171e09723e3fbb\System.Drawing.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3056.0
		Company: Microsoft Corporation

	Name: System.Windows.Forms.ni.dll
		Base address: 0x00007ffa5d910000
		Memory size: 0x00f4d000
		Entry point address: 0x0000000000000000
		File path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Windows.Forms\69ff356ffaef4c4c137570836532ba4d\System.Windows.Forms.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3056.0
		Company: Microsoft Corporation

	Name: HID.DLL
		Base address: 0x00007ffab60e0000
		Memory size: 0x0000c000
		Entry point address: 0x00007ffab60e1cb0
		File path: C:\WINDOWS\SYSTEM32\HID.DLL
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: DEVOBJ.dll
		Base address: 0x00007ffab71e0000
		Memory size: 0x00027000
		Entry point address: 0x00007ffab71e69c0
		File path: C:\WINDOWS\SYSTEM32\DEVOBJ.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: D3DCompiler_47.dll
		Base address: 0x00007ffab4b30000
		Memory size: 0x0042f000
		Entry point address: 0x00007ffab4d8e660
		File path: C:\WINDOWS\SYSTEM32\D3DCompiler_47.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: clbcatq.dll
		Base address: 0x00007ffaba350000
		Memory size: 0x000a0000
		Entry point address: 0x00007ffaba353cf0
		File path: C:\WINDOWS\System32\clbcatq.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: MMDevApi.dll
		Base address: 0x00007ffab2a00000
		Memory size: 0x00076000
		Entry point address: 0x00007ffab2a209e0
		File path: C:\WINDOWS\System32\MMDevApi.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: XAudio2_7.dll
		Base address: 0x00007ffa75d40000
		Memory size: 0x0008b000
		Entry point address: 0x00007ffa75db0650
		File path: C:\WINDOWS\system32\XAudio2_7.dll
		Product name: Microsoft® DirectX for Windows®
		Product version: 9.29.1962.0
		Company: Microsoft Corporation

	Name: AUDIOSES.DLL
		Base address: 0x00007ffa8d290000
		Memory size: 0x0012c000
		Entry point address: 0x00007ffa8d2a27b0
		File path: C:\WINDOWS\SYSTEM32\AUDIOSES.DLL
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: AVRT.dll
		Base address: 0x00007ffab18f0000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffab18f1000
		File path: C:\WINDOWS\SYSTEM32\AVRT.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: Windows.UI.dll
		Base address: 0x00007ffaaffa0000
		Memory size: 0x00114000
		Entry point address: 0x00007ffaaffcefd0
		File path: C:\Windows\System32\Windows.UI.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: System.Core.ni.dll
		Base address: 0x00007ffa728a0000
		Memory size: 0x00a50000
		Entry point address: 0x0000000000000000
		File path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Core\6a9fe8d059ff70adb50f5b340a4ad8ee\System.Core.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3160.0
		Company: Microsoft Corporation

	Name: System.Xml.ni.dll
		Base address: 0x00007ffa71230000
		Memory size: 0x0088c000
		Entry point address: 0x0000000000000000
		File path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Xml\08e8fa67f0a711551a8a00ad6c5880fc\System.Xml.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3056.0
		Company: Microsoft Corporation

	Name: System.Configuration.ni.dll
		Base address: 0x00007ffa749c0000
		Memory size: 0x0012a000
		Entry point address: 0x0000000000000000
		File path: C:\WINDOWS\assembly\NativeImages_v4.0.30319_64\System.Configuration\19daa5f5a704db96e4a812fa16f847fc\System.Configuration.ni.dll
		Product name: Microsoft® .NET Framework
		Product version: 4.7.3056.0
		Company: Microsoft Corporation

	Name: comctl32.dll
		Base address: 0x00007ffaaddc0000
		Memory size: 0x00269000
		Entry point address: 0x00007ffaade2bfe0
		File path: C:\WINDOWS\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17134.228_none_fb4599993062b194\comctl32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.228
		Company: Microsoft Corporation

	Name: gdiplus.dll
		Base address: 0x00007ffab0d00000
		Memory size: 0x0019a000
		Entry point address: 0x00007ffab0d51d30
		File path: C:\WINDOWS\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.17134.228_none_2c308c7e8af52b62\gdiplus.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.228
		Company: Microsoft Corporation

	Name: DWrite.dll
		Base address: 0x00007ffaa4e30000
		Memory size: 0x0031c000
		Entry point address: 0x00007ffaa4ed6310
		File path: C:\WINDOWS\SYSTEM32\DWrite.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: WindowsCodecs.dll
		Base address: 0x00007ffab1c40000
		Memory size: 0x001ae000
		Entry point address: 0x00007ffab1cd0410
		File path: C:\WINDOWS\SYSTEM32\WindowsCodecs.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: IconCodecService.dll
		Base address: 0x00007ffa9c240000
		Memory size: 0x00009000
		Entry point address: 0x00007ffa9c2419e0
		File path: C:\WINDOWS\system32\IconCodecService.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: gpapi.dll
		Base address: 0x00007ffab60f0000
		Memory size: 0x00022000
		Entry point address: 0x00007ffab60f2b20
		File path: C:\WINDOWS\SYSTEM32\gpapi.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: cryptnet.dll
		Base address: 0x00007ffaa9a20000
		Memory size: 0x0002e000
		Entry point address: 0x00007ffaa9a2d3c0
		File path: C:\Windows\System32\cryptnet.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: WINNSI.DLL
		Base address: 0x00007ffab1600000
		Memory size: 0x0000b000
		Entry point address: 0x00007ffab1601db0
		File path: C:\WINDOWS\SYSTEM32\WINNSI.DLL
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: NSI.dll
		Base address: 0x00007ffab9ef0000
		Memory size: 0x00008000
		Entry point address: 0x00007ffab9ef1f40
		File path: C:\WINDOWS\System32\NSI.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: socialclub.dll
		Base address: 0x00007ffa596f0000
		Memory size: 0x00af7200
		Entry point address: 0x00007ffa597f67e0
		File path: C:\Program Files\Rockstar Games\Social Club\socialclub.dll
		Product name: Social Club
		Product version: 1.2.4.0
		Company: Take-Two Interactive Software, Inc.

	Name: WININET.dll
		Base address: 0x00007ffaa04a0000
		Memory size: 0x0046e000
		Entry point address: 0x00007ffaa054e030
		File path: C:\WINDOWS\SYSTEM32\WININET.dll
		Product name: Internet Explorer
		Product version: 11.00.17134.165
		Company: Microsoft Corporation

	Name: napinsp.dll
		Base address: 0x00007ffaa3790000
		Memory size: 0x00016000
		Entry point address: 0x00007ffaa3791a60
		File path: C:\WINDOWS\system32\napinsp.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: pnrpnsp.dll
		Base address: 0x00007ffaa3770000
		Memory size: 0x0001a000
		Entry point address: 0x00007ffaa37722b0
		File path: C:\WINDOWS\system32\pnrpnsp.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: NLAapi.dll
		Base address: 0x00007ffab3fb0000
		Memory size: 0x00019000
		Entry point address: 0x00007ffab3fb55f0
		File path: C:\WINDOWS\system32\NLAapi.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: DNSAPI.dll
		Base address: 0x00007ffab69f0000
		Memory size: 0x000be000
		Entry point address: 0x00007ffab6a19350
		File path: C:\WINDOWS\SYSTEM32\DNSAPI.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: winrnr.dll
		Base address: 0x00007ffaa3760000
		Memory size: 0x0000e000
		Entry point address: 0x00007ffaa37613c0
		File path: C:\WINDOWS\System32\winrnr.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: fwpuclnt.dll
		Base address: 0x00007ffab1580000
		Memory size: 0x00072000
		Entry point address: 0x00007ffab1584e80
		File path: C:\WINDOWS\System32\fwpuclnt.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: rasadhlp.dll
		Base address: 0x00007ffaaddb0000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffaaddb1470
		File path: C:\Windows\System32\rasadhlp.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: FirewallAPI.dll
		Base address: 0x00007ffab63e0000
		Memory size: 0x0008a000
		Entry point address: 0x00007ffab63ea6b0
		File path: C:\Windows\System32\FirewallAPI.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: fwbase.dll
		Base address: 0x00007ffab6380000
		Memory size: 0x0002b000
		Entry point address: 0x00007ffab6388190
		File path: C:\Windows\System32\fwbase.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: FWPolicyIOMgr.dll
		Base address: 0x00007ffaaa690000
		Memory size: 0x00039000
		Entry point address: 0x00007ffaaa69a070
		File path: C:\Windows\System32\FWPolicyIOMgr.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.137
		Company: Microsoft Corporation

	Name: wdmaud.drv
		Base address: 0x00007ffa82b00000
		Memory size: 0x00044000
		Entry point address: 0x00007ffa82b079f0
		File path: C:\WINDOWS\SYSTEM32\wdmaud.drv
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: msacm32.drv
		Base address: 0x00007ffa9e2c0000
		Memory size: 0x0000d000
		Entry point address: 0x00007ffa9e2c44b0
		File path: C:\WINDOWS\SYSTEM32\msacm32.drv
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: MSACM32.dll
		Base address: 0x00007ffa829f0000
		Memory size: 0x0001c000
		Entry point address: 0x00007ffa829f3500
		File path: C:\WINDOWS\SYSTEM32\MSACM32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: midimap.dll
		Base address: 0x00007ffa9dfe0000
		Memory size: 0x0000a000
		Entry point address: 0x00007ffa9dfe1750
		File path: C:\WINDOWS\SYSTEM32\midimap.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: iertutil.dll
		Base address: 0x00007ffaaaec0000
		Memory size: 0x002a5000
		Entry point address: 0x00007ffaaaef4e00
		File path: C:\WINDOWS\SYSTEM32\iertutil.dll
		Product name: Internet Explorer
		Product version: 11.00.17134.165
		Company: Microsoft Corporation

	Name: ondemandconnroutehelper.dll
		Base address: 0x00007ffaa31a0000
		Memory size: 0x00015000
		Entry point address: 0x00007ffaa31a1dc0
		File path: C:\WINDOWS\SYSTEM32\ondemandconnroutehelper.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: winhttp.dll
		Base address: 0x00007ffab3380000
		Memory size: 0x000dc000
		Entry point address: 0x00007ffab33b9740
		File path: C:\WINDOWS\SYSTEM32\winhttp.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.165
		Company: Microsoft Corporation

	Name: wbemprox.dll
		Base address: 0x00007ffab2840000
		Memory size: 0x00011000
		Entry point address: 0x00007ffab28426d0
		File path: C:\WINDOWS\system32\wbem\wbemprox.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: wbemcomn.dll
		Base address: 0x00007ffab2760000
		Memory size: 0x00083000
		Entry point address: 0x00007ffab2776e60
		File path: C:\WINDOWS\SYSTEM32\wbemcomn.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: wbemsvc.dll
		Base address: 0x00007ffab2080000
		Memory size: 0x00014000
		Entry point address: 0x00007ffab2081790
		File path: C:\WINDOWS\system32\wbem\wbemsvc.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: fastprox.dll
		Base address: 0x00007ffab20a0000
		Memory size: 0x000f2000
		Entry point address: 0x00007ffab20d1bd0
		File path: C:\WINDOWS\system32\wbem\fastprox.dll
		Product name: Microsoft® Windows® Operating System
		Product version: 10.0.17134.1
		Company: Microsoft Corporation

	Name: comctl32.dll
		Base address: 0x00007ffab0ff0000
		Memory size: 0x000a7000
		Entry point address: 0x00007ffab1066ec0
		File path: C:\WINDOWS\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_5.82.17134.228_none_f95000f73097dead\comctl32.dll
		Product name: Betriebssystem Microsoft® Windows®
		Product version: 10.0.17134.228
		Company: Microsoft Corporation

Environment:
	TickCount: 23178046
	ExitCode: 0
	CommandLine: "C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe"
	CurrentDirectory: C:\Program Files\Rockstar Games\Grand Theft Auto V
	SystemDirectory: C:\WINDOWS\system32
	MachineName: DESKTOP-ALU87PT
	ProcessorCount: 4
	SystemPageSize: 4096
	Version: 4.0.30319.42000
	WorkingSet: 1255354368
	OSVersion: Microsoft Windows NT 6.2.9200.0
	Is64BitProcess: True
	Is64BitOperatingSystem: True
	HasShutdownStarted: False
	UserName: eroge
	UserInteractive: True
	UserDomainName: DESKTOP-ALU87PT
	CurrentManagedThreadId: 5

Process list:
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\explorer.exe)
	NVIDIA Share rel_03_13_1/8a2159c by NVIDIA Corporation (C:\Program Files (x86)\NVIDIA Corporation\NVIDIA GeForce Experience\NVIDIA Share.exe)
	WinRAR 5.50.0 by Alexander Roshal (C:\Program Files\WinRAR\WinRAR.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\NOTEPAD.EXE)
	Social Club UI 1.2.4.0 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\subprocess.exe)
	Intel(R) Common User Interface 6.15.10.4835 by Intel Corporation (C:\WINDOWS\system32\igfxHK.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	NVIDIA Share rel_03_13_1/8a2159c by NVIDIA Corporation (C:\Program Files (x86)\NVIDIA Corporation\NVIDIA GeForce Experience\NVIDIA Share.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Microsoft® Skype 12.1815.210.0 by Microsoft Corporation (C:\Program Files\WindowsApps\Microsoft.SkypeApp_12.1815.210.0_x64__kzf8qxf38zg5c\SkypeHost.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Xbox.Apps.GamingOverlay 1.16.180401004-rs4svcwack171341 by Microsoft Corporation (C:\Program Files\WindowsApps\Microsoft.XboxGamingOverlay_1.16.1004.0_x64__8wekyb3d8bbwe\GameBar.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (c:\windows\system32\taskhostw.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.1 by Microsoft Corporation (C:\Program Files\Windows NT\Accessories\WORDPAD.EXE)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	WinRAR 5.50.0 by Alexander Roshal (C:\Program Files\WinRAR\WinRAR.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	WinRAR 5.50.0 by Alexander Roshal (C:\Program Files\WinRAR\WinRAR.exe)
	Intel(R) Common User Interface 6.15.10.4835 by Intel Corporation (C:\WINDOWS\system32\igfxEM.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\WINDOWS\system32\SettingSyncHost.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\svchost.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\Explorer.EXE)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\NOTEPAD.EXE)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\NOTEPAD.EXE)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\WINDOWS\system32\DllHost.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\OpenWith.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\NOTEPAD.EXE)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	WinRAR 5.50.0 by Alexander Roshal (C:\Program Files\WinRAR\WinRAR.exe)
	NVIDIA Share rel_03_13_1/8a2159c by NVIDIA Corporation (C:\Program Files (x86)\NVIDIA Corporation\NVIDIA GeForce Experience\NVIDIA Share.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\NOTEPAD.EXE)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\conhost.exe)
	Steam Client Bootstrapper 01.00.00.01 by Valve Corporation (C:\Program Files (x86)\Steam\Steam.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Social Club UI 1.2.4.0 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\subprocess.exe)
	Microsoft Photos 2018.18051.1842000000-release2018.06 by Microsoft Corporation (C:\Program Files\WindowsApps\Microsoft.Windows.Photos_2018.18051.18420.0_x64__8wekyb3d8bbwe\Microsoft.Photos.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (C:\Program Files (x86)\Steam\bin\cef\cef.win7\steamwebhelper.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	WinRAR 5.50.0 by Alexander Roshal (C:\Program Files\WinRAR\WinRAR.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\SnippingTool.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (C:\Program Files (x86)\Steam\bin\cef\cef.win7\steamwebhelper.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Social Club UI 1.2.4.0 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\subprocess.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Grand Theft Auto V 1.0.1493.0 by Rockstar Games (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe)
	TeamSpeak 3 Client 3, 1, 8, 0 by TeamSpeak Systems GmbH (C:\Users\eroge\AppData\Local\TeamSpeak 3 Client\ts3client_win64.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\Windows\ImmersiveControlPanel\SystemSettings.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	OpenIV 3.0.0.0 by New Technology Studio (C:\Users\eroge\AppData\Local\New Technology Studio\Apps\OpenIV\OpenIV.exe)
	WinRAR 5.50.0 by Alexander Roshal (C:\Program Files\WinRAR\WinRAR.exe)
	  by  (C:\Program Files (x86)\NVIDIA Corporation\NvContainer\nvcontainer.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (C:\Program Files (x86)\Steam\bin\cef\cef.win7\steamwebhelper.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	WinRAR 5.50.0 by Alexander Roshal (C:\Program Files\WinRAR\WinRAR.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (C:\Program Files (x86)\Steam\bin\cef\cef.win7\steamwebhelper.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	WinRAR 5.50.0 by Alexander Roshal (C:\Program Files\WinRAR\WinRAR.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\NOTEPAD.EXE)
	Microsoft® Windows® Operating System 10.0.17134.228 by Microsoft Corporation (C:\Windows\SystemApps\Microsoft.Windows.Cortana_cw5n1h2txyewy\SearchUI.exe)
	Steam Client WebHelper 01.00.00.01 by Valve Corporation (C:\Program Files (x86)\Steam\bin\cef\cef.win7\steamwebhelper.exe)
	Microsoft® Windows® Operating System 10.0.17134.228 by Microsoft Corporation (C:\Windows\SystemApps\Microsoft.Windows.Cortana_cw5n1h2txyewy\RemindersServer.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\Windows\System32\RuntimeBroker.exe)
	Social Club UI 1.2.4.0 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\subprocess.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\WINDOWS\system32\ApplicationFrameHost.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\Windows\System32\GameBarPresenceWriter.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (c:\windows\system32\svchost.exe)
	Wallpaper Engine 1.0.0.0 by  (C:\Program Files (x86)\Steam\steamapps\common\wallpaper_engine\wallpaper64.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Microsoft Office 2016 16.0.10314.33875 by Microsoft Corporation (C:\Program Files\WindowsApps\Microsoft.MicrosoftOfficeHub_17.10314.31700.0_x64__8wekyb3d8bbwe\Office16\OfficeHubTaskHost.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\WINDOWS\system32\DllHost.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Social Club UI 1.2.4.0 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\subprocess.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\NOTEPAD.EXE)
	Grand Theft Auto V 1.0.1493.0 by Rockstar Games (C:\Program Files\Rockstar Games\Grand Theft Auto V\GTAVLauncher.exe)
	Node.js 6.12.2 by Node.js (C:\Program Files (x86)\NVIDIA Corporation\NvNode\NVIDIA Web Helper.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (c:\windows\system32\svchost.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (c:\windows\system32\sihost.exe)
	Social Club UI 1.2.4.0 by Take-Two Interactive Software, Inc. (C:\Program Files\Rockstar Games\Social Club\subprocess.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\WINDOWS\system32\conhost.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	  by  (C:\WINDOWS\system32\igfxTray.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	  by  (C:\Program Files (x86)\NVIDIA Corporation\NvContainer\nvcontainer.exe)
	Discord 0.0.301 by Discord Inc. (C:\Users\eroge\AppData\Local\Discord\app-0.0.301\Discord.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (c:\windows\system32\svchost.exe)
	Microsoft® Windows® Operating System 10.0.17134.1 by Microsoft Corporation (C:\WINDOWS\SystemApps\ShellExperienceHost_cw5n1h2txyewy\ShellExperienceHost.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Google Chrome 68.0.3440.106 by Google Inc. (C:\Program Files (x86)\Google\Chrome\Application\chrome.exe)
	Betriebssystem Microsoft® Windows® 10.0.17134.165 by Microsoft Corporation (C:\Windows\System32\smartscreen.exe)

File list: 
	C:\Program Files\Rockstar Games\Grand Theft Auto V\AddonSpawner.asi *fe2b8c47b3996fa12dc70b659900be00
	C:\Program Files\Rockstar Games\Grand Theft Auto V\AdvancedHook.log *aa4beb8009976ad3bac9210da6a388bb
	C:\Program Files\Rockstar Games\Grand Theft Auto V\AdvancedHookV.asi *90f62f92fdd55b2a259377ebef10627b
	C:\Program Files\Rockstar Games\Grand Theft Auto V\asiloader.log *2ea09d4cdbe366cfb65cab3481c1644b
	C:\Program Files\Rockstar Games\Grand Theft Auto V\bink2w64.dll *3722f03c488093cb2631b5412d4f12d9
	C:\Program Files\Rockstar Games\Grand Theft Auto V\commandline.txt *4977d75f267d3a4f92216dad9a8f25d1
	C:\Program Files\Rockstar Games\Grand Theft Auto V\common.rpf *bbe724acef5f9fcfd85a38c4e35e2f00
	C:\Program Files\Rockstar Games\Grand Theft Auto V\CrashReport_eroge_636702488854405755.rcr *25bb9d8b5909aceb8d9b809f9628f2b5
	C:\Program Files\Rockstar Games\Grand Theft Auto V\cursor_32_2.png *be981c7e1461188450c1bc0352aee019
	C:\Program Files\Rockstar Games\Grand Theft Auto V\d3dcompiler_46.dll *7ea872c2f9803cfb4223098b85e70cc0
	C:\Program Files\Rockstar Games\Grand Theft Auto V\d3dcsx_46.dll *8355e491fa90ca00045be22bb556b213
	C:\Program Files\Rockstar Games\Grand Theft Auto V\DefaultSkin.png *a7562ebd9a7c54a6575808da4680caf3
	C:\Program Files\Rockstar Games\Grand Theft Auto V\dinput8.dll *c9b973183908a6631b31ca29f863b4d1
	C:\Program Files\Rockstar Games\Grand Theft Auto V\FW1FontWrapper.dll *daa32fd4ee493fc1fdf0b66991868ef4
	C:\Program Files\Rockstar Games\Grand Theft Auto V\GFSDK_ShadowLib.win64.dll *f2c348c5aaff0c420f4dce3abc1bbad6
	C:\Program Files\Rockstar Games\Grand Theft Auto V\GFSDK_TXAA.win64.dll *167385d13443035ff68643b2c0c59a4d
	C:\Program Files\Rockstar Games\Grand Theft Auto V\GFSDK_TXAA_AlphaResolve.win64.dll *ea04393624856f44854cace25b50ce3c
	C:\Program Files\Rockstar Games\Grand Theft Auto V\GPUPerfAPIDX11-x64.dll *121044fe4ae47114dfccd15e399df399
	C:\Program Files\Rockstar Games\Grand Theft Auto V\GTA5.exe *db97f21d4c160903833966e826e8c2e9
	C:\Program Files\Rockstar Games\Grand Theft Auto V\GTAVLanguageSelect.exe *90da611b71d23b17c63f2899f1a8235f
	C:\Program Files\Rockstar Games\Grand Theft Auto V\GTAVLauncher.exe *4ea5147e60697e8b493216de8c4e1d5a
	C:\Program Files\Rockstar Games\Grand Theft Auto V\Gwen.dll *367a1b17121dfc7c2347984380939bc2
	C:\Program Files\Rockstar Games\Grand Theft Auto V\Gwen.UnitTest.dll *90b34cfce1f4caba67f42f4d8f135189
	C:\Program Files\Rockstar Games\Grand Theft Auto V\hashes.ini *dff1378013b7acea83961023611c69c2
	C:\Program Files\Rockstar Games\Grand Theft Auto V\LMS.Common.dll *61dfccfc5509df7e88bc4ab7eab982e1
	C:\Program Files\Rockstar Games\Grand Theft Auto V\LMS.PortableExecutable.dll *fa43b022de82641f3b620708edeccbf2
	C:\Program Files\Rockstar Games\Grand Theft Auto V\lspdfr_uinst.exe *175a8f0c4042b1314ba02ec384340c04
	C:\Program Files\Rockstar Games\Grand Theft Auto V\LUA.asi *4f5175c0b079cfd979936cc4b7516bf7
	C:\Program Files\Rockstar Games\Grand Theft Auto V\Microsoft.Expression.Drawing.dll *5bd39a82aacf1aa423e6eeeeda696eea
	C:\Program Files\Rockstar Games\Grand Theft Auto V\Mono.Cecil.dll *6d6292bc8e698e53e69556add6f62442
	C:\Program Files\Rockstar Games\Grand Theft Auto V\Mono.Cecil.Mdb.dll *3c6cff9ef0ba7748d6c61dfacb6890a7
	C:\Program Files\Rockstar Games\Grand Theft Auto V\Mono.Cecil.Pdb.dll *c7a0b5173df5bea531a20fbace30fc89
	C:\Program Files\Rockstar Games\Grand Theft Auto V\Mono.Cecil.Rocks.dll *7c9a0c59ce05aba61485eb46883ba933
	C:\Program Files\Rockstar Games\Grand Theft Auto V\NvPmApi.Core.win64.dll *2041025c15e6ff893dcbb5ed63fdb2f8
	C:\Program Files\Rockstar Games\Grand Theft Auto V\openCameraV.asi *33864c75d1b85563da56aff0ea794267
	C:\Program Files\Rockstar Games\Grand Theft Auto V\openCameraV.log *c33e527eabf2eea82afc4101ec04b685
	C:\Program Files\Rockstar Games\Grand Theft Auto V\OpenIV.asi *ef3de847eac7ba336e2d83ba96a8d61d
	C:\Program Files\Rockstar Games\Grand Theft Auto V\OpenIV.log *40ee5314fe92602b527421d6f7d7ad8a
	C:\Program Files\Rockstar Games\Grand Theft Auto V\PlayGTAV.exe *f78f447d4b72896d7549714c6842ac1b
	C:\Program Files\Rockstar Games\Grand Theft Auto V\RAGEPluginHook.euifl *f1af7fe1783392f8e2cb197e61ed5ee9
	C:\Program Files\Rockstar Games\Grand Theft Auto V\RAGEPluginHook.exe *ce43fb7f705d913c52bf223b9339a560
	C:\Program Files\Rockstar Games\Grand Theft Auto V\RagePluginHook.ini *ee499ad6d426e75a47411cccc0a96073
	C:\Program Files\Rockstar Games\Grand Theft Auto V\RagePluginHook.log *f252aa09b6f02f4f40126d89b10b1b54
	C:\Program Files\Rockstar Games\Grand Theft Auto V\Readme.txt *c742abc1d7f364bca097ca6599f2257c
	C:\Program Files\Rockstar Games\Grand Theft Auto V\ScriptHookV.dll *4909c295d92f9a6155c23a462a8e054c
	C:\Program Files\Rockstar Games\Grand Theft Auto V\ScriptHookV.log *76112e21ba357cb848e55062742cb17e
	C:\Program Files\Rockstar Games\Grand Theft Auto V\ScriptHookVDotNet.asi *1d67ceded00233d21a724952942e9fed
	C:\Program Files\Rockstar Games\Grand Theft Auto V\SlimDX.dll *5c243b42d2b0103bbe603cf586ea8467
	C:\Program Files\Rockstar Games\Grand Theft Auto V\startup.rphs *fc0873885922b9b3b1223b85aa0f7407
	C:\Program Files\Rockstar Games\Grand Theft Auto V\System.Data.SQLite.dll *d649b44e4af777192c42311050199450
	C:\Program Files\Rockstar Games\Grand Theft Auto V\TrainerV.asi *d675971032cccc59475723daaf15fccb
	C:\Program Files\Rockstar Games\Grand Theft Auto V\trainerv.ini *3dffae63be9cb9e83c8a224ddca378c6
	C:\Program Files\Rockstar Games\Grand Theft Auto V\version.txt *eb0ec566293a46f64f522242687722cb
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64a.rpf *683610e269ba60c5fcc7a9f6d1a8bfd5
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64b.rpf *70af24cd4fe2c8ee58edb902f018a558
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64c.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64d.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64e.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64f.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64g.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64h.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64i.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64j.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64k.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64l.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64m.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64n.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64o.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64p.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64q.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64r.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64s.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64t.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64u.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64v.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\x64w.rpf *Unknown
	C:\Program Files\Rockstar Games\Grand Theft Auto V\XInput1_4.dll *d2ef25dff3e2ad78f89a527101767707

Latest log:
19.08.2018 07:23:17.747] Started new log on 19.08.2018 07:23:17.747
[19.08.2018 07:23:17.770] ====================================================================================================
[19.08.2018 07:23:17.727] Log path: C:\Program Files\Rockstar Games\Grand Theft Auto V\RagePluginHook.log
[19.08.2018 07:23:17.772] Log verbosity: Trivial
[19.08.2018 07:23:17.774] Initializing input system
[19.08.2018 07:23:17.777] Initializing game console
[19.08.2018 07:23:17.787] Console key has been set to F4 (key code: 115)
[19.08.2018 07:23:17.868] Initializing console variable "ConsoleScrollAmount".
[19.08.2018 07:23:17.962] Type: System.Int32, Reading section: "Miscellaneous", key: ConsoleScrollAmount
[19.08.2018 07:23:17.966] Read value: <null>
[19.08.2018 07:23:17.981] Initializing console variable "DisableRenderVersionText".
[19.08.2018 07:23:17.981] Type: System.Boolean, Reading section: "Miscellaneous", key: DisableRenderVersionText
[19.08.2018 07:23:18.048] Read value: False
[19.08.2018 07:23:18.086] Setting value of console variable "DisableRenderVersionText" to stored value.
[19.08.2018 07:23:18.101] Initializing console variable "ConsoleKey".
[19.08.2018 07:23:18.106] Type: System.Windows.Forms.Keys, Reading section: "Miscellaneous", key: ConsoleKey
[19.08.2018 07:23:18.107] Read value: <null>
[19.08.2018 07:23:18.107] Initializing console variable "PluginTimeoutThreshold".
[19.08.2018 07:23:18.108] Type: System.Int32, Reading section: "Miscellaneous", key: PluginTimeoutThreshold
[19.08.2018 07:23:18.109] Read value: 10000
[19.08.2018 07:23:18.119] Setting value of console variable "PluginTimeoutThreshold" to stored value.
[19.08.2018 07:23:18.147] Initializing console variable "AlwaysShowConsoleOutput".
[19.08.2018 07:23:18.167] Type: System.Boolean, Reading section: "Miscellaneous", key: AlwaysShowConsoleOutput
[19.08.2018 07:23:18.169] Read value: <null>
[19.08.2018 07:23:18.171] Initializing console variable "ShowConsoleCommandInfoOnPluginLoad".
[19.08.2018 07:23:18.171] Type: System.Boolean, Reading section: "Miscellaneous", key: ShowConsoleCommandInfoOnPluginLoad
[19.08.2018 07:23:18.172] Read value: <null>
[19.08.2018 07:23:18.172] Initializing console variable "ShowOnScreenWarnings".
[19.08.2018 07:23:18.173] Type: System.Boolean, Reading section: "Miscellaneous", key: ShowOnScreenWarnings
[19.08.2018 07:23:18.174] Read value: <null>
[19.08.2018 07:23:18.174] Console initialized
[19.08.2018 07:23:18.174] Initializing forms manager
[19.08.2018 07:23:18.178] Version: RAGE Plugin Hook v0.63.1224.15140 PUBLIC ALPHA for Grand Theft Auto V
[19.08.2018 07:23:18.206] ================ RAGE Plugin Hook ================
[19.08.2018 07:23:18.226] Detected Windows 10 Home (64-bit) (10.0.17134.0)!
[19.08.2018 07:23:18.239] Checking game support
[19.08.2018 07:23:18.594] Product name: Grand Theft Auto V
[19.08.2018 07:23:18.602] Product version: 1.0.1493.0
[19.08.2018 07:23:18.602] Is steam version: False
[19.08.2018 07:23:18.604] Initializing DirectX
[19.08.2018 07:23:18.611] Initializing Direct3D
[19.08.2018 07:23:18.615] Loading C:\WINDOWS\system32\d3d11.dll
[19.08.2018 07:23:18.615] Loaded at 0x7FFAB4820000
[19.08.2018 07:23:18.615] D3D11CreateDeviceAndSwapChain at 0x7FFAB4835950
[19.08.2018 07:23:18.615] Creating Direct3D 11 device and swap chain
[19.08.2018 07:23:18.656] Attempting feature level 10_1
[19.08.2018 07:23:18.701] Failed to create D3D11 device for Grand Theft Auto V: 887a0001
[19.08.2018 07:23:18.740] Attempting feature level 10_1 for fallback
[19.08.2018 07:23:18.822] Fall back attempt failed with: 887a0001!
[19.08.2018 07:23:18.825] Initialized DirectX
[19.08.2018 07:23:49.516] LoadingScreenMsg: Initializing game support
[19.08.2018 07:23:49.768] Initializing game support
[19.08.2018 07:23:50.434] LoadingScreenMsg: Velocity limit removed
[19.08.2018 07:23:50.759] Compatibility level: 0
[19.08.2018 07:23:50.759] Supported version detected
[19.08.2018 07:23:50.760] ==================================================
[19.08.2018 07:23:50.760] LoadingScreenMsg: Patching code
[19.08.2018 07:23:51.012] LoadingScreenMsg: Waiting for game initialization

