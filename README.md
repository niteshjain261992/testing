## Referral

### Description
Referral is simple sharing feature that gives power to user to share some product or block
with their friends and get respective discount or wallet points

### Model

   * #### Title (string):
      Title is to understand the description of referral
   * #### Conditions (Array Object):
      Condition gives power to admin to add different conditions according to their need, currently
      we are supporting only story, order and conversation condition
   * #### Type (string):
     This variable is used to define type of referral (wallet/template)
       * ##### Wallet:
           To update wallet points in wallet after user accept offer.
       * ##### Template:
           To fire template after user accept offer.
   * #### Referee (Object):
      This variable is used to define discount/wallets points in percentage/flat for referee.
   * #### Referrer (Object):
      This variable is used to define discount/wallets points in percentage/flat for referrer.
   * #### Invite Discount (Object):
      This variable is used to define discount/wallets points to first time referee.
   * #### Max Referee (Number):
      This variable is used to define maximum discount to referee. 
   * #### Max Referrer (Number):
      This variable is used to define maximum cashback to referrer after user accepts offer
   * #### Referee Block     



