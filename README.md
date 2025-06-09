# Adminer on Vercel PHP Runtime

This project deploys Adminer, a lightweight database management tool, on Vercel using their PHP runtime.

## Structure

- `api/index.php`: Entry point for the Vercel PHP runtime
- `adminer.php`: The Adminer database management tool
- `vercel.json`: Configuration for Vercel deployment
- `composer.json`: PHP dependencies

## Deployment

To deploy this project to Vercel:

1. Install the Vercel CLI:
   ```
   npm i -g vercel
   ```

2. Login to Vercel:
   ```
   vercel login
   ```

3. Deploy the project:
   ```
   vercel
   ```

## Local Development

For local development, you can use PHP's built-in server:

```
php -S localhost:8000 -t api/
```
