Tabla Chat con AWS DynamoDB

| PK         | SK                                        | connectionId    | message                                    | url | attributes                                                                                 |
|------------|-------------------------------------------|-----------------|--------------------------------------------|-----|--------------------------------------------------------------------------------------------|
| fromUserId | CONNECTION_REQUEST_${toUserId}            |                 | Hola, me gustaria añadirte a mis contactos |     |                                                                                            |
| toUserId   | BLOCKED_USER_${fromUserId} |                 |                                            |     |                                                                                            |
| chatId     | PARTICIPANT_${userId}                     |                 |                                            |     |                                                                                            |
| chatId     | MESSAGE_${userId}_${DATE}                 |                 | ¡Hola, encantado de conocerte!             |     | {   "audio": "s3.com" \| null,   "image": "s3.com" \| null,   "video": "s3.com" \| null }  |
| userId     | CONNECTION                                | ${connectionId} |                                            |     | {   "status": "disconnected" \| "unavailable" \| null,   "notifications": true \| false, } |
