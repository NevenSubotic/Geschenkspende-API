# Geschenkspende-API
Another API which returns a PDF based on a Slide Template.

# Payload
nameFrom - Name of person paying for the Donation. Sender.
nameTo - Name of person who is gifted the Donation. Recipient.
amount - The amount of the Donation.
messageToRecipient - Optional. Sender can send a custom message to the Recipient.

# Return
isSuccess - Boolean.
asBlob - Blob of the generated PDF.
url - Url of the PDF which is stored in G-Drive.
msg - Returns error text if isSuccess is false

# Logging
Logging is done via Stackdriver.
Records are also logged to the Container Sheet of the GAS-Project.
