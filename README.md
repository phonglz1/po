<?xml version="1.0" encoding="utf-8"?>
<!-- Created with Broadpeak BkS350 Origin Packager  (version=1.11.2-24244) -->
<MPD xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="urn:mpeg:dash:schema:mpd:2011" xmlns:cenc="urn:mpeg:cenc:2013" xmlns:mspr="urn:microsoft:playready" xsi:schemaLocation="urn:mpeg:dash:schema:mpd:2011 http://standards.iso.org/ittf/PubliclyAvailableStandards/MPEG-DASH_schema_files/DASH-MPD.xsd" type="dynamic" availabilityStartTime="1970-01-01T00:00:00Z" publishTime="2022-02-03T13:57:09.584400Z" minimumUpdatePeriod="PT2S" timeShiftBufferDepth="PT59.968S" maxSegmentDuration="PT3S" minBufferTime="PT10S" profiles="urn:mpeg:dash:profile:isoff-live:2011,urn:com:dashif:dash264">
  <Period id="1" start="PT0S">
    <BaseURL>dash/</BaseURL>
    <AdaptationSet id="1" group="1" contentType="audio" lang="vi" segmentAlignment="true" audioSamplingRate="32000" mimeType="audio/mp4" codecs="mp4a.40.29" startWithSAP="1">
      <AudioChannelConfiguration schemeIdUri="urn:mpeg:dash:23003:3:audio_channel_configuration:2011" value="1"/>
      <!-- Common Encryption -->
      <ContentProtection schemeIdUri="urn:mpeg:dash:mp4protection:2011" value="cenc" cenc:default_KID="914CEE52-54D2-425B-B1C3-1B199F571A71">
      </ContentProtection>
      <!-- PlayReady -->
      <ContentProtection schemeIdUri="urn:uuid:9A04F079-9840-4286-AB92-E65BE0885F95" value="MSPR 2.0">
        <cenc:pssh>AAACmHBzc2gAAAAAmgTweZhAQoarkuZb4IhflQAAAnh4AgAAAQABAG4CPABXAFIATQBIAEUAQQBEAEUAUgAgAHgAbQBsAG4AcwA9ACIAaAB0AHQAcAA6AC8ALwBzAGMAaABlAG0AYQBzAC4AbQBpAGMAcgBvAHMAbwBmAHQALgBjAG8AbQAvAEQAUgBNAC8AMgAwADAANwAvADAAMwAvAFAAbABhAHkAUgBlAGEAZAB5AEgAZQBhAGQAZQByACIAIAB2AGUAcgBzAGkAbwBuAD0AIgA0AC4AMAAuADAALgAwACIAPgA8AEQAQQBUAEEAPgA8AFAAUgBPAFQARQBDAFQASQBOAEYATwA+ADwASwBFAFkATABFAE4APgAxADYAPAAvAEsARQBZAEwARQBOAD4APABBAEwARwBJAEQAPgBBAEUAUwBDAFQAUgA8AC8AQQBMAEcASQBEAD4APAAvAFAAUgBPAFQARQBDAFQASQBOAEYATwA+ADwASwBJAEQAPgBVAHUANQBNAGsAZABKAFUAVwAwAEsAeAB3AHgAcwBaAG4AMQBjAGEAYwBRAD0APQA8AC8ASwBJAEQAPgA8AEwAQQBfAFUAUgBMAD4AaAB0AHQAcAA6AC8ALwBpAGQAeAAuAHMAbwBsAG8AYwBvAG8ALgB0AHYALwBpAGQAeAAvAGQAcgBtAC4AYQBzAHAAeAAvAHAAcgAvAHMAZwA8AC8ATABBAF8AVQBSAEwAPgA8AEMASABFAEMASwBTAFUATQA+AGIAbwBvAE8AdwBBAEIARQA1AEwAawA9ADwALwBDAEgARQBDAEsAUwBVAE0APgA8AC8ARABBAFQAQQA+ADwALwBXAFIATQBIAEUAQQBEAEUAUgA+AA==</cenc:pssh>
        <mspr:IsEncrypted>1</mspr:IsEncrypted>
        <mspr:IV_Size>8</mspr:IV_Size>
        <mspr:kid>Uu5MkdJUW0KxwxsZn1cacQ==</mspr:kid>
        <mspr:pro>eAIAAAEAAQBuAjwAVwBSAE0ASABFAEEARABFAFIAIAB4AG0AbABuAHMAPQAiAGgAdAB0AHAAOgAvAC8AcwBjAGgAZQBtAGEAcwAuAG0AaQBjAHIAbwBzAG8AZgB0AC4AYwBvAG0ALwBEAFIATQAvADIAMAAwADcALwAwADMALwBQAGwAYQB5AFIAZQBhAGQAeQBIAGUAYQBkAGUAcgAiACAAdgBlAHIAcwBpAG8AbgA9ACIANAAuADAALgAwAC4AMAAiAD4APABEAEEAVABBAD4APABQAFIATwBUAEUAQwBUAEkATgBGAE8APgA8AEsARQBZAEwARQBOAD4AMQA2ADwALwBLAEUAWQBMAEUATgA+ADwAQQBMAEcASQBEAD4AQQBFAFMAQwBUAFIAPAAvAEEATABHAEkARAA+ADwALwBQAFIATwBUAEUAQwBUAEkATgBGAE8APgA8AEsASQBEAD4AVQB1ADUATQBrAGQASgBVAFcAMABLAHgAdwB4AHMAWgBuADEAYwBhAGMAUQA9AD0APAAvAEsASQBEAD4APABMAEEAXwBVAFIATAA+AGgAdAB0AHAAOgAvAC8AaQBkAHgALgBzAG8AbABvAGMAbwBvAC4AdAB2AC8AaQBkAHgALwBkAHIAbQAuAGEAcwBwAHgALwBwAHIALwBzAGcAPAAvAEwAQQBfAFUAUgBMAD4APABDAEgARQBDAEsAUwBVAE0APgBiAG8AbwBPAHcAQQBCAEUANQBMAGsAPQA8AC8AQwBIAEUAQwBLAFMAVQBNAD4APAAvAEQAQQBUAEEAPgA8AC8AVwBSAE0ASABFAEEARABFAFIAPgA=</mspr:pro>
      </ContentProtection>
      <!-- Widevine -->
      <ContentProtection schemeIdUri="urn:uuid:EDEF8BA9-79D6-4ACE-A3C8-27DCD51D21ED">
        <cenc:pssh>AAAAWXBzc2gAAAAA7e+LqXnWSs6jyCfc1R0h7QAAADkIARIQkUzuUlTSQluxwxsZn1cacRoLc3RyZWFtZ3JvdXAiEFLuTJHSVFtCscMbGZ9XGnEqAlNEMgA=</cenc:pssh>
      </ContentProtection>
      <Role schemeIdUri="urn:mpeg:dash:role:2011" value="main"/>
      <SegmentTemplate timescale="32000" initialization="prod_kplus_kidshd-$RepresentationID$.dash" media="prod_kplus_kidshd-$RepresentationID$-$Time$.dash">
        <!-- 2022-02-03T13:56:05.515500Z / 1643896565 - 2022-02-03T13:57:05.483500Z -->
        <SegmentTimeline>
          <S t="52604690096496" d="63488" r="1"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
        </SegmentTimeline>
      </SegmentTemplate>
      <Representation id="audio_87682_vie=87200" bandwidth="87200">
      </Representation>
    </AdaptationSet>
    <AdaptationSet id="2" group="1" contentType="audio" lang="qaa" segmentAlignment="true" audioSamplingRate="32000" mimeType="audio/mp4" codecs="mp4a.40.29" startWithSAP="1">
      <AudioChannelConfiguration schemeIdUri="urn:mpeg:dash:23003:3:audio_channel_configuration:2011" value="1"/>
      <!-- Common Encryption -->
      <ContentProtection schemeIdUri="urn:mpeg:dash:mp4protection:2011" value="cenc" cenc:default_KID="914CEE52-54D2-425B-B1C3-1B199F571A71">
      </ContentProtection>
      <!-- PlayReady -->
      <ContentProtection schemeIdUri="urn:uuid:9A04F079-9840-4286-AB92-E65BE0885F95" value="MSPR 2.0">
        <cenc:pssh>AAACmHBzc2gAAAAAmgTweZhAQoarkuZb4IhflQAAAnh4AgAAAQABAG4CPABXAFIATQBIAEUAQQBEAEUAUgAgAHgAbQBsAG4AcwA9ACIAaAB0AHQAcAA6AC8ALwBzAGMAaABlAG0AYQBzAC4AbQBpAGMAcgBvAHMAbwBmAHQALgBjAG8AbQAvAEQAUgBNAC8AMgAwADAANwAvADAAMwAvAFAAbABhAHkAUgBlAGEAZAB5AEgAZQBhAGQAZQByACIAIAB2AGUAcgBzAGkAbwBuAD0AIgA0AC4AMAAuADAALgAwACIAPgA8AEQAQQBUAEEAPgA8AFAAUgBPAFQARQBDAFQASQBOAEYATwA+ADwASwBFAFkATABFAE4APgAxADYAPAAvAEsARQBZAEwARQBOAD4APABBAEwARwBJAEQAPgBBAEUAUwBDAFQAUgA8AC8AQQBMAEcASQBEAD4APAAvAFAAUgBPAFQARQBDAFQASQBOAEYATwA+ADwASwBJAEQAPgBVAHUANQBNAGsAZABKAFUAVwAwAEsAeAB3AHgAcwBaAG4AMQBjAGEAYwBRAD0APQA8AC8ASwBJAEQAPgA8AEwAQQBfAFUAUgBMAD4AaAB0AHQAcAA6AC8ALwBpAGQAeAAuAHMAbwBsAG8AYwBvAG8ALgB0AHYALwBpAGQAeAAvAGQAcgBtAC4AYQBzAHAAeAAvAHAAcgAvAHMAZwA8AC8ATABBAF8AVQBSAEwAPgA8AEMASABFAEMASwBTAFUATQA+AGIAbwBvAE8AdwBBAEIARQA1AEwAawA9ADwALwBDAEgARQBDAEsAUwBVAE0APgA8AC8ARABBAFQAQQA+ADwALwBXAFIATQBIAEUAQQBEAEUAUgA+AA==</cenc:pssh>
        <mspr:IsEncrypted>1</mspr:IsEncrypted>
        <mspr:IV_Size>8</mspr:IV_Size>
        <mspr:kid>Uu5MkdJUW0KxwxsZn1cacQ==</mspr:kid>
        <mspr:pro>eAIAAAEAAQBuAjwAVwBSAE0ASABFAEEARABFAFIAIAB4AG0AbABuAHMAPQAiAGgAdAB0AHAAOgAvAC8AcwBjAGgAZQBtAGEAcwAuAG0AaQBjAHIAbwBzAG8AZgB0AC4AYwBvAG0ALwBEAFIATQAvADIAMAAwADcALwAwADMALwBQAGwAYQB5AFIAZQBhAGQAeQBIAGUAYQBkAGUAcgAiACAAdgBlAHIAcwBpAG8AbgA9ACIANAAuADAALgAwAC4AMAAiAD4APABEAEEAVABBAD4APABQAFIATwBUAEUAQwBUAEkATgBGAE8APgA8AEsARQBZAEwARQBOAD4AMQA2ADwALwBLAEUAWQBMAEUATgA+ADwAQQBMAEcASQBEAD4AQQBFAFMAQwBUAFIAPAAvAEEATABHAEkARAA+ADwALwBQAFIATwBUAEUAQwBUAEkATgBGAE8APgA8AEsASQBEAD4AVQB1ADUATQBrAGQASgBVAFcAMABLAHgAdwB4AHMAWgBuADEAYwBhAGMAUQA9AD0APAAvAEsASQBEAD4APABMAEEAXwBVAFIATAA+AGgAdAB0AHAAOgAvAC8AaQBkAHgALgBzAG8AbABvAGMAbwBvAC4AdAB2AC8AaQBkAHgALwBkAHIAbQAuAGEAcwBwAHgALwBwAHIALwBzAGcAPAAvAEwAQQBfAFUAUgBMAD4APABDAEgARQBDAEsAUwBVAE0APgBiAG8AbwBPAHcAQQBCAEUANQBMAGsAPQA8AC8AQwBIAEUAQwBLAFMAVQBNAD4APAAvAEQAQQBUAEEAPgA8AC8AVwBSAE0ASABFAEEARABFAFIAPgA=</mspr:pro>
      </ContentProtection>
      <!-- Widevine -->
      <ContentProtection schemeIdUri="urn:uuid:EDEF8BA9-79D6-4ACE-A3C8-27DCD51D21ED">
        <cenc:pssh>AAAAWXBzc2gAAAAA7e+LqXnWSs6jyCfc1R0h7QAAADkIARIQkUzuUlTSQluxwxsZn1cacRoLc3RyZWFtZ3JvdXAiEFLuTJHSVFtCscMbGZ9XGnEqAlNEMgA=</cenc:pssh>
      </ContentProtection>
      <Role schemeIdUri="urn:mpeg:dash:role:2011" value="main"/>
      <SegmentTemplate timescale="32000" initialization="prod_kplus_kidshd-$RepresentationID$.dash" media="prod_kplus_kidshd-$RepresentationID$-$Time$.dash">
        <!-- 2022-02-03T13:56:05.515500Z / 1643896565 - 2022-02-03T13:57:05.483500Z -->
        <SegmentTimeline>
          <S t="52604690096496" d="63488" r="1"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
          <S d="65536"/>
          <S d="63488" r="2"/>
        </SegmentTimeline>
      </SegmentTemplate>
      <Representation id="audio_87683_qaa=87200" bandwidth="87200">
      </Representation>
    </AdaptationSet>
    <AdaptationSet id="3" group="2" contentType="video" par="16:9" minBandwidth="1087600" maxBandwidth="2662400" maxWidth="1920" maxHeight="1080" segmentAlignment="true" sar="1:1" frameRate="25" mimeType="video/mp4" startWithSAP="1">
      <!-- Common Encryption -->
      <ContentProtection schemeIdUri="urn:mpeg:dash:mp4protection:2011" value="cenc" cenc:default_KID="914CEE52-54D2-425B-B1C3-1B199F571A71">
      </ContentProtection>
      <!-- PlayReady -->
      <ContentProtection schemeIdUri="urn:uuid:9A04F079-9840-4286-AB92-E65BE0885F95" value="MSPR 2.0">
        <cenc:pssh>AAACmHBzc2gAAAAAmgTweZhAQoarkuZb4IhflQAAAnh4AgAAAQABAG4CPABXAFIATQBIAEUAQQBEAEUAUgAgAHgAbQBsAG4AcwA9ACIAaAB0AHQAcAA6AC8ALwBzAGMAaABlAG0AYQBzAC4AbQBpAGMAcgBvAHMAbwBmAHQALgBjAG8AbQAvAEQAUgBNAC8AMgAwADAANwAvADAAMwAvAFAAbABhAHkAUgBlAGEAZAB5AEgAZQBhAGQAZQByACIAIAB2AGUAcgBzAGkAbwBuAD0AIgA0AC4AMAAuADAALgAwACIAPgA8AEQAQQBUAEEAPgA8AFAAUgBPAFQARQBDAFQASQBOAEYATwA+ADwASwBFAFkATABFAE4APgAxADYAPAAvAEsARQBZAEwARQBOAD4APABBAEwARwBJAEQAPgBBAEUAUwBDAFQAUgA8AC8AQQBMAEcASQBEAD4APAAvAFAAUgBPAFQARQBDAFQASQBOAEYATwA+ADwASwBJAEQAPgBVAHUANQBNAGsAZABKAFUAVwAwAEsAeAB3AHgAcwBaAG4AMQBjAGEAYwBRAD0APQA8AC8ASwBJAEQAPgA8AEwAQQBfAFUAUgBMAD4AaAB0AHQAcAA6AC8ALwBpAGQAeAAuAHMAbwBsAG8AYwBvAG8ALgB0AHYALwBpAGQAeAAvAGQAcgBtAC4AYQBzAHAAeAAvAHAAcgAvAHMAZwA8AC8ATABBAF8AVQBSAEwAPgA8AEMASABFAEMASwBTAFUATQA+AGIAbwBvAE8AdwBBAEIARQA1AEwAawA9ADwALwBDAEgARQBDAEsAUwBVAE0APgA8AC8ARABBAFQAQQA+ADwALwBXAFIATQBIAEUAQQBEAEUAUgA+AA==</cenc:pssh>
        <mspr:IsEncrypted>1</mspr:IsEncrypted>
        <mspr:IV_Size>8</mspr:IV_Size>
        <mspr:kid>Uu5MkdJUW0KxwxsZn1cacQ==</mspr:kid>
        <mspr:pro>eAIAAAEAAQBuAjwAVwBSAE0ASABFAEEARABFAFIAIAB4AG0AbABuAHMAPQAiAGgAdAB0AHAAOgAvAC8AcwBjAGgAZQBtAGEAcwAuAG0AaQBjAHIAbwBzAG8AZgB0AC4AYwBvAG0ALwBEAFIATQAvADIAMAAwADcALwAwADMALwBQAGwAYQB5AFIAZQBhAGQAeQBIAGUAYQBkAGUAcgAiACAAdgBlAHIAcwBpAG8AbgA9ACIANAAuADAALgAwAC4AMAAiAD4APABEAEEAVABBAD4APABQAFIATwBUAEUAQwBUAEkATgBGAE8APgA8AEsARQBZAEwARQBOAD4AMQA2ADwALwBLAEUAWQBMAEUATgA+ADwAQQBMAEcASQBEAD4AQQBFAFMAQwBUAFIAPAAvAEEATABHAEkARAA+ADwALwBQAFIATwBUAEUAQwBUAEkATgBGAE8APgA8AEsASQBEAD4AVQB1ADUATQBrAGQASgBVAFcAMABLAHgAdwB4AHMAWgBuADEAYwBhAGMAUQA9AD0APAAvAEsASQBEAD4APABMAEEAXwBVAFIATAA+AGgAdAB0AHAAOgAvAC8AaQBkAHgALgBzAG8AbABvAGMAbwBvAC4AdAB2AC8AaQBkAHgALwBkAHIAbQAuAGEAcwBwAHgALwBwAHIALwBzAGcAPAAvAEwAQQBfAFUAUgBMAD4APABDAEgARQBDAEsAUwBVAE0APgBiAG8AbwBPAHcAQQBCAEUANQBMAGsAPQA8AC8AQwBIAEUAQwBLAFMAVQBNAD4APAAvAEQAQQBUAEEAPgA8AC8AVwBSAE0ASABFAEEARABFAFIAPgA=</mspr:pro>
      </ContentProtection>
      <!-- Widevine -->
      <ContentProtection schemeIdUri="urn:uuid:EDEF8BA9-79D6-4ACE-A3C8-27DCD51D21ED">
        <cenc:pssh>AAAAWXBzc2gAAAAA7e+LqXnWSs6jyCfc1R0h7QAAADkIARIQkUzuUlTSQluxwxsZn1cacRoLc3RyZWFtZ3JvdXAiEFLuTJHSVFtCscMbGZ9XGnEqAlNEMgA=</cenc:pssh>
      </ContentProtection>
      <Role schemeIdUri="urn:mpeg:dash:role:2011" value="main"/>
      <SegmentTemplate timescale="600" initialization="prod_kplus_kidshd-$RepresentationID$.dash" media="prod_kplus_kidshd-$RepresentationID$-$Time$.dash">
        <!-- 2022-02-03T13:56:07.480000Z / 1643896567 - 2022-02-03T13:57:07.480000Z -->
        <SegmentTimeline>
          <S t="986337940488" d="1200" r="29"/>
        </SegmentTimeline>
      </SegmentTemplate>
      <Representation id="video=1087600" bandwidth="1087600" width="640" height="360" codecs="avc1.4D401E" scanType="progressive">
      </Representation>
      <Representation id="video=2137600" bandwidth="2137600" width="1280" height="720" codecs="avc1.4D401F" scanType="progressive">
      </Representation>
      <Representation id="video=2662400" bandwidth="2662400" width="1920" height="1080" codecs="avc1.4D4028" scanType="progressive">
      </Representation>
    </AdaptationSet>
  </Period>
  <UTCTiming schemeIdUri="urn:mpeg:dash:utc:http-iso:2014" value="https://time.akamai.com/?iso"/>
</MPD>
