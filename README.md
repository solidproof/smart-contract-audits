# smart-contract-audits 1642822290197,START,GetDynamicKeyHelper.setupDefaultToken:defaultApin:serverURL:params:,,
1642822290200,INFO,GetDynamicKeyHelper.setupDefaultToken:defaultApin:serverURL:params:,,result: 1 - defaultToken: WX67DAFCC2 - ServerURL: https://innovative-partners.digibank.vn/provision/
1642822290200,END,GetDynamicKeyHelper.setupDefaultToken:defaultApin:serverURL:params:,0.000081,
1642822290200,START,GetDynamicKeyHelper.setupActivation:requestActivated:,,
1642822290201,INFO,GetDynamicKeyHelper.setupActivation:requestActivated:,,result: 1 - ServerURL: https://innovative-partners.digibank.vn/provision/activate
1642822290201,END,GetDynamicKeyHelper.setupActivation:requestActivated:,0.000187,
1642822291719,START,RN startTAOv2
1642822291719,START,TAOSecure.startTAO,,
1642822291721,INFO,TAOSecure.startTAO,,vtapStatus: 101
1642822291722,END,TAOSecure.startTAO,0.002171,
1642822291722,INFO,startTAO code: 101
1642822291722,START,GetDynamicKeyHelper.isDynamicKeyProvisioning,,
1642822291722,INFO,GetDynamicKeyHelper.isDynamicKeyProvisioning,,all tokens: (null)
1642822291723,INFO,GetDynamicKeyHelper.isDynamicKeyProvisioning,,DynToken: WX67DAFCC2 - DynToken in AllToken?: 0
1642822291723,END,GetDynamicKeyHelper.isDynamicKeyProvisioning,0.000057,
1642822291723,START,GetDynamicKeyHelper.getDefaultDynamicToken:,,
1642822291723,START,GetDynamicKeyHelper.doGetFirmware,,
1642822291972,START,GetDynamicKeyHelper.postURLConnection:endpoint:options:handleType:,,
1642822291972,END,GetDynamicKeyHelper.postURLConnection:endpoint:options:handleType:,0.000371,
1642822291973,END,GetDynamicKeyHelper.doGetFirmware,0.251237,
1642822291973,END,GetDynamicKeyHelper.getDefaultDynamicToken:,0.251261,
1642822292954,START,GetDynamicKeyHelper.handleRespone:res:handleType:error:,,SECURE_HTTP_CONN_FIRMWARE
1642822292957,START,GetDynamicKeyHelper.saveAndGenerateFirmwarePath:,,
1642822292959,END,GetDynamicKeyHelper.saveAndGenerateFirmwarePath:,0.001975,
1642822292959,INFO,GetDynamicKeyHelper.handleRespone:res:handleType:error:,,Download Firmware success - filePath: /var/mobile/Containers/Data/Application/E530FCB2-A106-4932-8FBC-A5BA46C76AFA/Documents/download.json
1642822292960,START,GetDynamicKeyHelper.doProvisioningFlow2:withApin:downloadFilePath:,,
1642822292960,START,GetDynamicKeyHelper.loadFirmware:,,
1642822293223,END,GetDynamicKeyHelper.loadFirmware:,0.264010,
1642822293224,INFO,GetDynamicKeyHelper.doProvisioningFlow2:withApin:downloadFilePath:,,Provisioning Result: 40608
1642822293224,START,GetDynamicKeyHelper.processFinish:resultInt:, request code: 101
1642822293224,START,GetDynamicKeyHelper.setOtpTaPin:,,
1642822293268,INFO,GetDynamicKeyHelper.setOtpTaPin:,,createPinStatus: 40700
1642822293372,INFO,GetDynamicKeyHelper.setOtpTaPin:,,checkTokenPinStatus: 40800
1642822293374,INFO,GetDynamicKeyHelper.setOtpTaPin:,,setOTPLengthStatus: 41000
1642822293375,END,GetDynamicKeyHelper.setOtpTaPin:,0.150934,
1642822293375,START,GetDynamicKeyHelper.activatedDynamicKey,,
1642822293376,START,activatedDynamicKey
1642822293376,START,GetDynamicKeyHelper.doGenerateOTP,,
1642822293594,INFO,GetDynamicKeyHelper.doGenerateOTP,,OTP Length: 8
1642822293594,END,GetDynamicKeyHelper.doGenerateOTP,0.219389,
1642822293594,START,GetDynamicKeyHelper.postURLConnection:endpoint:options:handleType:,,
1642822293594,END,GetDynamicKeyHelper.postURLConnection:endpoint:options:handleType:,0.000342,
1642822293595,END,GetDynamicKeyHelper.activatedDynamicKey,0.219811,
1642822293595,END,GetDynamicKeyHelper.processFinish:resultInt:,0.370804,
1642822293595,END,GetDynamicKeyHelper.doProvisioningFlow2:withApin:downloadFilePath:,0.634888,
1642822293927,START,GetDynamicKeyHelper.handleRespone:res:handleType:error:,,SHTTP_ACTIVATE_DYNKEY
1642822293927,INFO,GetDynamicKe
