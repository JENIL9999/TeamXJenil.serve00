<?php
// CORS headers to allow cross-origin requests
header("Access-Control-Allow-Origin: *");
header("Content-Type: application/json");

// Get parameters from frontend
$uid = isset($_GET['uid']) ? $_GET['uid'] : '';
$server_name = isset($_GET['server_name']) ? $_GET['server_name'] : '';

// Validate input
if (empty($uid) || empty($server_name)) {
    echo json_encode(['status' => 0, 'message' => 'UID or Server name missing']);
    exit;
}

// Construct API URL
$api_url = "https://chx-likes.vercel.app/like?uid={$uid}&server_name={$server_name}";

// Get API response
$response = file_get_contents($api_url);

// Check if response is received
if ($response === FALSE) {
    echo json_encode(['status' => 0, 'message' => 'Failed to connect to the API']);
    exit;
}

// Return the API response
echo $response;
?>