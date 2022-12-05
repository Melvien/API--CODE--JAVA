import { Router } from "express";


// Expro
const router = Router()



router.get('/', (req, res) => {
  res.send('/posts/ route')
});

export default router