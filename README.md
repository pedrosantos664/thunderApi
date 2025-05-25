# thunderApi

npm i express

npm install prisma --save-dev

npx prisma init

em prisma/schema.prisma add:
model User {
  id      String   @id @default(auto()) @map("_id") @db.ObjectId
  email   String   @unique
  name    String
  age     String
  
}

npx prima db push
npm install @prisma/client
npx prisma studio
