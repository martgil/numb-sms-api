# numb-sms-api

Numb SMS API is a free SMS API for sending text messages.

>Note: Only philippine mobile number is currently supported.

Link to the API: https://numb-sms.herokuapp.com

## Usage
JSON parameters are used to communicate with API server.

Please refer to the following endpoint below:

<details>
  <summary>POST /sendMessage</summary>
  <table>
    <thead>
      <tr>
        <td>Parameter Name</td>
        <td>Type</td>
        <td>Description</td>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>api_token</td>
        <td>string</td>
        <td>API token consume.</td>
      </tr>
      <tr>
        <td>recipient</td>
        <td>string</td>
        <td>Recipient's phone number starting with +63 international mobile number format for PH.</td>
      </tr>
      <tr>
        <td>name</td>
        <td>string</td>
        <td>Sender name</td>
      </tr>
      <tr>
        <td>msg</td>
        <td>string</td>
        <td>Desired message to send.</td>
      </tr>
    </tbody>
  </table> 
</details>

Please send an <a href="mailto:twosince85@gmail.com">email</a> to request an API token for free.
