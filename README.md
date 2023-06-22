# newco1pr15mb4841b9fb7bb334c84e9adea3f15da@co1pr15mb4841.namprd15.prod.outlook.comco1pr15mb4841b9fb7bb334c84e9adea3f15daX-Google-Smtp-Source: ACHHUZ7CFM12qFsFNx9Lz6mxsonwVRgUnwPZC0kp9jszptspY6pgMPn0sy0IiNUH2agmsiXvPwOV
X-Received: by 2002:a05:6a00:b44:b0:668:79d6:34df with SMTP id p4-20020a056a000b4400b0066879d634dfmr11694815pfo.23.1687366314032;
        Wed, 21 Jun 2023 09:51:54 -0700 (PDT)
ARC-Seal: i=2; a=rsa-sha256; t=1687366314; cv=pass;
        d=google.com; s=arc-20160816;
        b=by1WEAE/9UwRDBxtJU9Hc1Jtwe4SrHhI2Gl4o7uWteYjmSObKHK3Es/tNZqog0qjg2
         gjLhNVM08GGSZH1x8VlwPBrn4UQBARYCRu6os/tD20YMM8QyunZzsOE1hbIDjvKIinpH
         erdyzo9MwyIYK3F0lvkPCAg1wbZZ7OeTPixdutoeB5kCIlLpFE6PaUFkJwNKF3y5NkWF
         f0fSb3oADvNbHsPyabflsAUgJ6huygn8S8LWwmp6+kehsbGHz64gaEoraLDdVMmczHdq
         f7u5/cu7hv/h76IbH42AwMjlXf0+cj6EvZzEYqCfQA5YdzmLzKWTs9oQ39s9PxDahQ9S
         8iQg==
ARC-Message-Signature: i=2; a=rsa-sha256; c=relaxed/relaxed; d=google.com; s=arc-20160816;
        h=mime-version:content-language:accept-language:message-id:date
         :thread-index:thread-topic:subject:to:from:dkim-signature;
        bh=neHRfDzU2qxe2C2E/+JECfXVRld2PN+dUbsV9ciK6ic=;
        b=wkDEUTD5mEGVZJbdQ7HjgsEtrJwBZpNcWwckZevtHmhIOg01VnpyyiScm/oZa2y11Y
         b2TgoQeKG3dTXfQ350fUnBkNxtqJj59Z1dc8hrnGEyVVNlN8ywjRUYoG8ygn8OhipfIx
         SHF1Htle86OEPsm7eJ1Hru5bQAzoh7gEcT8FyAnPlOU0B9ciXaEsNZuo56TxzTRBEVyO
         +jABdApALvg9J1gKa5ymGrAky/gZAlC9MYw/nzskVkZExHgWWz7SFUsc97HADfXsMyzv
        ACHHUZ7CFM12qFsFNx9Lz6mxsonwVRgUnwPZC0kp9jszptspY6pgMPn0sy0IiNUH2agmsiXvPwOV
X-Received: by 2002:a05:6a00:b44:b0:668:79d6:34df with SMTP id p4-20020a056a000b4400b0066879d634dfmr11694815pfo.23.1687366314032;
        Wed, 21 Jun 2023 09:51:54 -0700 (PDT)
ARC-Seal: i=2; a=rsa-sha256; t=1687366314; cv=pass;
        d=google.com; s=arc-20160816;
       CO1PR15MB4841B9FB7BB334C84E9ADEA3F15DA@CO1PR15MB4841.namprd15.prod.outlook.com
