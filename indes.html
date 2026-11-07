package com.example.ui.screens.drawer

import android.content.Intent
import android.net.Uri
import android.widget.Toast
import androidx.compose.foundation.background
import androidx.compose.foundation.layout.Arrangement
import androidx.compose.foundation.layout.Column
import androidx.compose.foundation.layout.Row
import androidx.compose.foundation.layout.Spacer
import androidx.compose.foundation.layout.fillMaxSize
import androidx.compose.foundation.layout.fillMaxWidth
import androidx.compose.foundation.layout.height
import androidx.compose.foundation.layout.padding
import androidx.compose.foundation.layout.size
import androidx.compose.foundation.layout.width
import androidx.compose.foundation.rememberScrollState
import androidx.compose.foundation.shape.RoundedCornerShape
import androidx.compose.foundation.verticalScroll
import androidx.compose.material.icons.Icons
import androidx.compose.material.icons.outlined.OpenInBrowser
import androidx.compose.material.icons.outlined.Security
import androidx.compose.material3.Button
import androidx.compose.material3.ButtonDefaults
import androidx.compose.material3.Card
import androidx.compose.material3.CardDefaults
import androidx.compose.material3.Icon
import androidx.compose.material3.Text
import androidx.compose.runtime.Composable
import androidx.compose.ui.Alignment
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.Color
import androidx.compose.ui.platform.LocalContext
import androidx.compose.ui.platform.testTag
import androidx.compose.ui.text.font.FontWeight
import androidx.compose.ui.unit.dp
import androidx.compose.ui.unit.sp
import com.example.ui.theme.DarkBackground
import com.example.ui.theme.PrizeGold
import com.example.ui.theme.SurfaceDark
import com.example.ui.theme.TextMuted
import com.example.ui.theme.TextWhite

private const val PLACEHOLDER_POLICY_URL = "[PRIVACY POLICY URL REQUIRED]"
private const val PLACEHOLDER_CONTACT_EMAIL = "officialmondalgroup@gmail.com"
private const val PLACEHOLDER_LEGAL_ENTITY = "[LEGAL ENTITY DETAILS REQUIRED, IF APPLICABLE]"

@Composable
fun PrivacyPolicyScreen() {
    val context = LocalContext.current

    Column(
        modifier = Modifier
            .fillMaxSize()
            .background(DarkBackground)
            .verticalScroll(rememberScrollState())
            .padding(horizontal = 20.dp, vertical = 24.dp)
            .testTag("screen_privacy_policy"),
        verticalArrangement = Arrangement.spacedBy(16.dp)
    ) {
        // Header
        Row(verticalAlignment = Alignment.CenterVertically) {
            Icon(
                imageVector = Icons.Outlined.Security,
                contentDescription = null,
                tint = PrizeGold,
                modifier = Modifier.size(26.dp)
            )
            Spacer(modifier = Modifier.width(10.dp))
            Column {
                Text(
                    text = "Privacy Policy",
                    color = TextWhite,
                    fontSize = 22.sp,
                    fontWeight = FontWeight.Bold
                )
                Text(
                    text = "Effective Date: November 2026 • Version 1.0",
                    color = TextMuted,
                    fontSize = 12.sp
                )
            }
        }

        // External Policy URL Card
        Card(
            modifier = Modifier.fillMaxWidth(),
            colors = CardDefaults.cardColors(containerColor = Color(0xFF0F172A)),
            shape = RoundedCornerShape(14.dp),
            border = androidx.compose.foundation.BorderStroke(1.dp, Color(0xFF1E293B))
        ) {
            Column(modifier = Modifier.padding(16.dp)) {
                Text(
                    text = "Official Hosted Privacy Policy URL:",
                    color = PrizeGold,
                    fontSize = 12.sp,
                    fontWeight = FontWeight.Bold
                )
                Text(
                    text = PLACEHOLDER_POLICY_URL,
                    color = Color(0xFF94A3B8),
                    fontSize = 12.sp
                )
                Spacer(modifier = Modifier.height(10.dp))
                Button(
                    onClick = {
                        Toast.makeText(
                            context,
                            "External Policy URL will be hosted before Google Play submission ($PLACEHOLDER_POLICY_URL)",
                            Toast.LENGTH_LONG
                        ).show()
                    },
                    colors = ButtonDefaults.buttonColors(containerColor = Color(0xFF1E293B)),
                    shape = RoundedCornerShape(8.dp),
                    modifier = Modifier.fillMaxWidth()
                ) {
                    Icon(imageVector = Icons.Outlined.OpenInBrowser, contentDescription = null, modifier = Modifier.size(16.dp))
                    Spacer(modifier = Modifier.width(8.dp))
                    Text("View Online Privacy Policy", color = TextWhite, fontSize = 13.sp)
                }
            }
        }

        // Section 1: Overview & Scope
        PolicySectionCard(
            title = "1. Introduction & Overview",
            body = "Lottery Result (referred to as \"we\", \"our\", or \"the app\"), operated by $PLACEHOLDER_LEGAL_ENTITY, respects your personal privacy. This Privacy Policy discloses our data collection, processing, and storage practices in connection with your use of the Lottery Result Android application.\n\nWe do not require user account registration, passwords, or personal login profiles to browse lottery results."
        )

        // Section 2: Permissions & Data Collection
        PolicySectionCard(
            title = "2. Device Permissions & Information Processed",
            body = "The application requests and utilizes only the following minimum necessary Android permissions:\n\n" +
                    "• INTERNET (android.permission.INTERNET): Allows the app to connect securely to public result servers to download public lottery draw announcements and authentic official PDF records.\n\n" +
                    "• ACCESS NETWORK STATE (android.permission.ACCESS_NETWORK_STATE): Used to detect active internet connectivity, allowing the app to serve locally stored results when offline.\n\n" +
                    "• ADVERTISING ID (com.google.android.gms.permission.AD_ID): Required under Android 13+ for the Google Mobile Ads SDK to deliver compliant advertising."
        )

        // Section 3: Third-Party SDKs & Advertising
        PolicySectionCard(
            title = "3. Third-Party Services & Advertising (Google AdMob)",
            body = "The app integrates the Google Mobile Ads (AdMob) SDK to display advertisements. AdMob may collect and process pseudonymous identifiers, such as the Android Advertising ID, IP address, device diagnostic information, and coarse network location to serve relevant ads.\n\n" +
                    "You may manage or reset your advertising preferences at any time through your Android system settings under Settings > Google > Ads.\n\n" +
                    "The app also utilizes Google ML Kit Text Recognition for on-device ticket scanning. Ticket image processing occurs entirely locally on your device hardware; images are never transmitted or stored on remote servers."
        )

        // Section 4: Data Storage & Retention
        PolicySectionCard(
            title = "4. Local Storage & Data Retention",
            body = "The app stores public lottery draw records and queries on local device storage to enable instant offline access without re-downloading previously viewed results.\n\n" +
                    "We do not collect or store names, email addresses, phone numbers, banking details, or exact GPS locations on our servers.\n\n" +
                    "Users can manage or clear locally stored application data at any time through standard Android system settings (Settings > Apps > Lottery Result > Storage)."
        )

        // Section 5: Children's Privacy
        PolicySectionCard(
            title = "5. Children's Privacy",
            body = "Lottery Result is intended strictly for users who have attained the legal age for lottery reference in their jurisdiction (18+). The app does not knowingly collect personal information from children under the age of 13."
        )

        // Section 6: Contact Information
        PolicySectionCard(
            title = "6. Contact & Privacy Inquiries",
            body = "If you have questions regarding this Privacy Policy or wish to exercise your data privacy rights, please contact our Data Protection Officer at:\n\n" +
                    "Email: $PLACEHOLDER_CONTACT_EMAIL\n" +
                    "Legal Entity: $PLACEHOLDER_LEGAL_ENTITY"
        )

        Spacer(modifier = Modifier.height(20.dp))
    }
}

@Composable
private fun PolicySectionCard(title: String, body: String) {
    Card(
        modifier = Modifier.fillMaxWidth(),
        colors = CardDefaults.cardColors(containerColor = SurfaceDark),
        shape = RoundedCornerShape(14.dp),
        border = androidx.compose.foundation.BorderStroke(1.dp, Color(0xFF1E293B))
    ) {
        Column(modifier = Modifier.padding(18.dp)) {
            Text(
                text = title,
                color = PrizeGold,
                fontSize = 15.sp,
                fontWeight = FontWeight.Bold
            )
            Spacer(modifier = Modifier.height(8.dp))
            Text(
                text = body,
                color = Color(0xFFCBD5E1),
                fontSize = 13.sp,
                lineHeight = 19.sp
            )
        }
    }
}
