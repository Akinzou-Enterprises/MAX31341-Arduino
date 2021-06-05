# MAX31341-Arduino <br />
MAX31341 Arduino lib <br />

MAX31341 RTC; <br />

RTC.begin(ClkInterput ClkIn, WaveOutputFrequency WaveOutputFreq, bool Oscilator, bool ExternalClockInput, bool INTCN) //begin <br />
RTC.RTCsettings(bool I2Ctimeout, BREF voltage, bool DataRetend) //RTC settings <br />

setting time: <br />
RTC.SetHour(21); <br />
RTC.SetMinutes(37); <br />
RTC.SetRTCData(); //dont forget about that <br />
