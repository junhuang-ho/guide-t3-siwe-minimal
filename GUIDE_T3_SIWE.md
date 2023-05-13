[for next-auth: "^4.21.0" - unsure for future versions]

1. yarn create t3-app
2. maintain next to be "^13.2.6" [not strictly related to t3+SIWE]
3. install @rainbow-me/rainbowkit >= 1.0.0
4. install @rainbow-me/rainbowkit-siwe-next-auth >= 0.2.0
5. install "ethers": "^5.6.8",
6. install "siwe": "^2.1.4",
7. install "viem": "~0.3.19", - TEST
8. install "wagmi": "^1.0.1"
9. rmb add NEXTAUTH_SECRET in .env
10. edit `server/auth.ts` according to https://github.com/codingwithmanny/t3-app-siwe/tree/fix/next-auth-4.21.1
11. edit `pages/api/auth/[...nextauth].ts` according to https://github.com/codingwithmanny/t3-app-siwe/tree/fix/next-auth-4.21.1
12. edit `_app.tsx` and `index.tsx` as usual
13. --
