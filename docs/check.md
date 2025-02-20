if [ -d "build" ] && [ -n "$(ls -A build 2>/dev/null)" ]; then
echo "✅ Build completed successfully."
else
echo "❌ Build failed. Exiting..."
exit 1
fi
